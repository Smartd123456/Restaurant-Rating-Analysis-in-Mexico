# Restaurant-Rating-Analysis-in-Mexico
This project analyzes restaurant ratings in Mexico to uncover what drives customer satisfaction. Using data on cuisine types, pricing, franchise status, and location, it identifies key trends and customer preferences. The goal is to highlight what makes a restaurant top-rated and reveal market opportunities for restaurant owners and investors.

# Project Overview
This project explores restaurant ratings in Mexico to understand what makes a restaurant successful in the eyes of customers. By analyzing a variety of features - such as cuisine type, price level, alcohol service, smoking policy, franchise status, and city distribution, i uncover the patterns and preferences that drive high ratings.
The analysis goes beyond identifying top-rated restaurants. It digs into consumer behavior, possible data biases, and supply-demand gaps within the market. These insights help answer practical questions like:
- What characteristics are common among the highest-rated restaurants?
- Are certain cities or cuisines over-or under-represented?
- Which market segments show unmet demand?
- If you were to invest in a new restaurant, what features should you prioritize?
- Whether you are a data enthusiast, a restaurant owner, or an investor, this project provides a clear, data-backed view of the Mexican         restaurant landscape-and what it takes to thrive in it.
  
## Project Goal
The main objective of this project is to analyze restaurant ratings in Mexico and uncover the key factors that influence customer satisfaction. By exploring trends in customer preferences, restaurant characteristics, and market distribution, the project aims to:
- Identify common traits among the highest-rated restaurants
- Understand how factors like cuisine, pricing, alcohol service, and smoking policy affect ratings
- Detect possible data biases or imbalances in the sample
- Reveal market gaps and under-served segments that present business opportunities
- Provide data-driven recommendations for investors or restaurant owners looking to enter or expand in the Mexican market.
  
## Tools Used
- Power BI – For data cleaning, transformation, interactive visualizations, and dashboard creation.
- Power Query Editor – To manage missing values, reformat columns, and filter relevant data.
- DAX (Data Analysis Expressions) – To create custom measures and calculated columns for deeper analysis.
- Microsoft Excel – For initial data exploration and formatting.
- PowerPoint – Used to design and style the dashboard background for a polished visual presentation.
  
## Key Features And Dax Formulas
This project was built in Power BI to explore restaurant ratings across Mexico. Below are the key features of the project and the custom DAX formulas used to power the dashboard.
 ### Key Features
- Interactive Dashboard:
  Users can filter by city, cuisine, price, and more to explore restaurant trends.
- Top-Rated Restaurant Analysis:
   Identifies what makes a restaurant successful based on customer ratings.
- Market Gap Insights:
  Highlights cities and cuisines with fewer restaurants but high demand.
- Customer Preference Breakdown:
Shows what people prefer based on price, alcohol policy, and smoking options.
- Clean Visual Design:
 Background created using PowerPoint for a professional look.
- Business-Friendly Recommendations:
 Suggestions for restaurant owners and investors based on real data.
### DAX Formulas Used
These simple DAX formulas were used to calculate the main figures shown in the dashboard:
-  Total numbers of cities = DISTINCTCOUNT(consumers[City]).
-  Average overall rating = AVERAGE('ratings 1'[Overall_Rating]).
-  total numbers of customers = COUNT(consumers[Consumer_ID]).
-  total numbers of prefer cuisines = DISTINCTCOUNT(consumer_preferences[Preferred_Cuisine]).
-  Total restaurants = COUNTROWS(restaurants)


## Project Workflow
This project followed a structured process from data collection to insight delivery. Below is a breakdown of each step:
-  Data Collection:
  Obtained restaurant rating data for Mexico from a public dataset.
- Verified columns for restaurant name, city, rating, cuisine, price, alcohol policy, smoking policy, and more.
-  Data Cleaning (Power BI – Power Query):
   Removed duplicates and null values.
-  Standardized column names and formats (e.g. text casing, currency).
- Categorized numerical values.
-  Data Transformation:
  Created calculated columns and measures.
-  Dashboard Design:
  Designed a clean and intuitive layout using PowerPoint for the background.
- Built an interactive Power BI dashboard with filters for city, cuisine, and other key dimensions.
-  Insight Generation:
  Identified top-performing restaurants and common traits.
- Highlighted market gaps and customer preferences.
- Analyzed demand by region, price level, and service policies.

## Business Questions
This project aimed to answer key business questions that could guide restaurant owners, investors, and marketers in making data-driven decisions:
- Question 1:
  What can you learn from the highest rated restaurants? Do consumer preferences have an effect on
 ratings?
- Question 2:
 What are the consumer demographics? Does this indicate a bias in the data sample?
- Question 3:
  Are there any demand & supply gaps that you can exploit in the market?
- Question 4:
  If you were to invest in a restaurant, which characteristics would you be looking for?

## Analysis and insights
All insights were generated based on visual analysis of the dataset using Power BI. Various charts, filters, and measures were used to explore:
- Customer preferences and behavior
- Restaurant performance across cities and cuisines
- Market trends based on price, alcohol and smoking policies
- Areas with high ratings but low restaurant presence (market gaps).
 Each visual on the dashboard tells a specific story, helping users make informed decisions based on real data.

## Recommendation
If you are planning to open or invest in a restaurant in Mexico, the data suggests a few smart moves:
- Open in San Luis Potosí - There are a lot of customers but not many restaurants.
- Serve Mexican food – It is the most loved and top-rated cuisine.
- Keep prices affordable-Most people prefer low-budget restaurants.
- Focus on students and young people- They make up most of the customers.
- Be near public transport-That is how most customers get around.
- Franchises are rare but do well- There is room to grow in this area.
- Avoid alcohol and smoking- Restaurants without these often get better ratings.
- These choices are backed by the numbers and can help attract more customers and increase restaurant success.

## Conclusion
This analysis shows that successful restaurants in Mexico align closely with local preferences-affordable prices, familiar cuisines like Mexican food, and convenient access matter most. Restaurants like Tortas, which consistently perform well in food, service, and overall ratings, offer a clear model to follow. By understanding customer behavior and filling regional gaps in supply, investors and restaurant owners can make smarter, data-driven decisions that lead to better customer satisfaction and business growth.

## Author
Happiness Friday Bassey - Data analytics


























