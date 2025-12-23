# Swiggy-Data-Analysis
Exploratory data analysis of Swiggy food delivery data to uncover customer behavior, restaurant performance, and delivery insights using Python.
A complete Exploratory Data Analysis (EDA) project performed on the Swiggy food delivery dataset to understand customer ordering behavior, restaurant performance, pricing trends, and delivery efficiency.
This project uses Python, Pandas, NumPy, Matplotlib, and Seaborn for in-depth data exploration and insightful visualizations.

1. Project Overview
> The goal of this analysis is to examine:
> Customer ordering patterns
> Restaurant pricing and ratings
> Delivery time behavior
> Cuisine and city-wise trends
> Key factors influencing customer satisfaction
> Relationships between price, ratings, delivery speed, and demand.


2. Dataset Description
The dataset contains information about restaurants listed on Swiggy and their performance metrics.

| Column          | Type        | Description                        |
| --------------- | ----------- | ---------------------------------- |
| restaurant_name | Categorical | Name of the restaurant             |
| city            | Categorical | City where the restaurant operates |
| cuisine         | Categorical | Type of cuisine offered            |
| price (INR)     | Numeric     | Average price for one order        |
| rating          | Numeric     | Customer rating (out of 5)         |
| rating_count    | Numeric     | Number of ratings received         |
| delivery_time   | Numeric     | Average delivery time (minutes)    |
| offers          | Categorical | Availability of discounts/offers   |
| veg_nonveg      | Categorical | Veg / Non-Veg category             |


3. EDA Framework
A systematic approach was followed to explore and understand the dataset.

3.1 Data Loading
> Loaded the dataset using Pandas
> Displayed sample records
> Checked column data types and structure

3.2 Data Cleaning
> Handled missing and inconsistent values
> Removed duplicate records
> Treated extreme outliers in price and delivery time
> Standardized categorical values
> Converted incorrect data types


4. Exploratory Data Analysis (EDA)

4.1 Univariate Analysis
.Distribution of restaurant prices
.Rating distribution
.Rating count patterns
.Delivery time distribution
.Cuisine frequency analysis
.City-wise restaurant count

4.2 Bivariate Analysis
.Price vs Rating
.Delivery Time vs Rating
.Rating vs Rating Count
.Cuisine vs Average Rating
.City vs Average Price
.Veg vs Non-Veg restaurant performance

4.3 Multivariate Analysis
.Combined impact of price, rating count, and ratings
.Delivery time + pricing + customer satisfaction
.High-order restaurants across multiple dimensions

5. Key Insights
.Faster delivery significantly improves customer ratings
.Mid-priced restaurants often outperform expensive ones
.Rating count strongly influences rating stability
.Certain cuisines consistently perform better across cities
.High prices do not guarantee better customer experience
.Customer trust is driven by consistency, not discounts alone

6. Correlation Heatmap (Numerical Features)
.Most numerical relationships are weak to moderate
.Rating count has a stronger influence on ratings than price
.Delivery time negatively impacts customer satisfaction
.Customer demand depends on multiple interacting factors

7. Visualizations Used
> Histograms
> Countplots
> Boxplots
> Scatterplots
> Barplots
> Heatmaps
> Pairplots (focused on key features)

8. Conclusion

This EDA provides a clear understanding of food delivery dynamics on Swiggy, highlighting that customer satisfaction and demand are influenced by:
Delivery speed
Consistent ratings
Competitive pricing
Cuisine preferences
City-level demand patterns

The dataset reflects real-world food delivery behavior:
Reliable restaurants receive more reviews and higher ratings
Mid-priced outlets dominate customer demand
Experience matters more than premium pricing

This analysis builds a strong foundation for:
Restaurant recommendation systems
Demand forecasting
Customer segmentation
Predictive modeling

9. Technologies Used
> Python
> Pandas
> NumPy
> Matplotlib
> Seaborn
> Jupyter Notebook
