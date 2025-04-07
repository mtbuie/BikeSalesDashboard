# Bike Sales Dashboard in Excel

# Objective
A supposed Cycling company was to look into what kind of demographics are buying their bikes. They want a visual can look at to easily parse the data they have. 

-Goal
To create visualizations for the demographics of people who purchase bikes.

-Plan
Create tables and pivot tables using excel. 
The following fields will be used for the pivot tables:

1.Average Income Per Purchase
2.Customer Commute
3.Age Bracket

# Data Source
The data is sourced from Kaggle. It is a collection of a 1000 various [Bike Buyers}(https://www.kaggle.com/datasets/heeraldedhia/bike-buyers).

# Tools used

-Microsoft Excel

# Data Exploration
 There are 13 columns in total listing the average information for a customer. Each customer comes with a unique ID. Using Find and Select we have found no null values or cells filled with errors.

 ![bike_table_raw](assets/images/bike_buyers_raw.PNG)

# Data Cleaning

The data is already in a pretty useable state. We will only make a few slight formatting adjustments.

1. Removed duplicates
2. Extend the abbreviations of Martial Status and Gender into their full words for readability.
3. Removed empty decimal places.
4. There are various ages listed across the dataset. So we will add a new column that groups them into age brackets:
   -Adolescent
   -Middle Age
   -Old
![bike_table_cleaned](assets/images/bike_buyers_table.PNG)

# Pivot Tables and Charts

Now that our data is ready we will create pivot table and graphs to use them.

## Average Income

Pivot Table covering the customer's average income and whether or not they purchased a bicycle. Graph is a bar char separated by male and female.

![Average Income](assets/images/average_income.PNG)

## Commute Distance

The distance customers travel during their daily commutes. Used a line chart for the visual.

![Commute Distance](assets/images/customer_commute.PNG)

## Age Range

The purchasing decisions separated by age brackets. Used a line chart to visualize.

![Age Bracket](assets/images/age_brackets.PNG)

# Dashboard

Now that we have all of our charts, we will build the dashboard.

1. Created a header to title the dashboard.
2. Placed and ogranized our 3 charts.
3. Added slicers for marital status, region, and education level so that the data can be filtered.

![Bike Dashboard](assets/images/bike_dashboard_alone.PNG)

![Bike Dashboard Preview](assets/images/bike_dashboard_test.gif)

# Insights

 There are some key takeaways we can immediately get from this information. Those with larger incomes are more likely to purchase bikes. Married couples buy more bikes than single customers. Likely bought as a pair to ride together. When it comes to age, the largest amount of bikes are bought by those in their middle age. Those with with longer commutes don't buy as many bikes and opt for other modes transportation. And lastly, people with higher levels of education bought more bikes. 



