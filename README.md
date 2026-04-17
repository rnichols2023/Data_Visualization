## 🌟 Midwest Data Exploration — README
Welcome to my analysis of the Midwest dataset from the ggplot2 package.
This project explores demographic, geographic, and population‑related patterns across counties in the Midwestern United States.

The goal of this report is to understand the structure of the dataset, visualize key relationships, and highlight meaningful insights.

## 📁 Dataset Overview
The Midwest dataset contains county‑level information for several Midwestern states. Below is a quick reference for each column:

## 🧱 Column Descriptions
Column	Meaning
PID – Unique identifier for each county  
county – Name of the county  
state – State where the county is located  
area – Land area of the county (in thousands of square miles)  
poptotal – Total population of the county  
popdensity – Population density (people per square mile)  
popwhite – White population count  
popblack – Black population count  
popamerindian – American Indian population count  
popasian – Asian population count  
popother – Population count of other racial groups  
percwhite – Percent of population that is White  
percblack – Percent of population that is Black  
percamerindan – Percent of population that is American Indian  
percasian – Percent of population that is Asian  
percother – Percent of population that is Other  
popadults – Adult population (18 and older)  
percollege – Percent of adults with a college degree  
percprof – Percent of adults in professional occupations  
percpoverty – Percent of population below the poverty line  
percbelowpoverty – Duplicate of percpoverty (included in dataset)  
percchildbelowpovert – Percent of children below the poverty line  
percadultpoverty – Percent of adults below the poverty line  
percelderlypoverty – Percent of elderly individuals below the poverty line  
inmetro – Indicates whether the county is part of a metropolitan area (1 = yes, 0 = no)  
category – County classification category (A, B, C, etc.)  

## 📊 Visualizations & What They Reveal
Below is a summary of each visualization used in the project and why it matters.

## 🟦 1. Bar Plot — Count of Counties by State
Why this visualization helps:  
A bar plot quickly shows how many counties each state contributes to the dataset.

What we learn:  
Some states have far more counties than others, which affects comparisons. For example, Illinois and Ohio have many counties, while others have fewer — meaning some states naturally dominate the dataset.

## 🔄 2. Horizontal Bar Plot — Same Data, Different Perspective
Why this visualization helps:  
Horizontal bars improve readability when category names (state names) are long.

What we learn:  
Same insight as above, but easier to read — especially useful when presenting to others.

## 📈 3. Histogram — Total Population Distribution
Why this visualization helps:  
Histograms show how population is distributed across counties.

What we learn:  
Most counties have relatively small populations, with a few very large outliers. This tells us the Midwest has many rural counties and a handful of major population centers.

## 📉 4. Histogram — Population Density
Why this visualization helps:  
Population density reveals how crowded or spread out counties are.

What we learn:  
Density is extremely skewed — most counties are sparsely populated, with a few dense urban areas. This reinforces the rural–urban divide in the Midwest.

## 🔵 5. Scatterplot — Area vs. Population Density
Why this visualization helps:  
Scatterplots show relationships between two continuous variables.

What we learn:  
There is a clear negative relationship:

Larger counties tend to have lower population density

Smaller counties tend to be more urban and dense

This makes intuitive sense — rural counties cover more land.

## 📉 6. Line Plot — Area vs. Population Density (Line Version)
Why this visualization helps:  
A line plot is not ideal for unordered county data, but it demonstrates how density fluctuates across counties when sorted by area.

What we learn:  
The pattern reinforces the scatterplot: density drops as area increases.

## 🧩 7. Stacked Bar Plot — Category by State
Why this visualization helps:  
Stacked bars show how county categories (A, B, C, etc.) are distributed across states.

What we learn:  
Some states have more counties in certain categories, which may reflect differences in:

economic conditions

population structure

urbanization

regional classification systems

This helps identify structural differences between states.

## 🧠 Key Takeaways
The Midwest is dominated by rural, low‑density counties.

A small number of counties account for most of the population.

County area and population density have a strong inverse relationship.

States vary widely in the number and type of counties they contain.

Visualizations help reveal patterns that raw tables cannot show.

## 🙌 Final Thoughts
This project demonstrates how exploratory data analysis (EDA) can uncover meaningful patterns in demographic data. By combining summary statistics with clear visualizations, we gain a deeper understanding of the Midwest’s population structure and geographic diversity.
