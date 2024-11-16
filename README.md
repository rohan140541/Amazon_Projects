# Amazon_Projects

Project Flow - Start -> Data Collection and Preprocessing -> EDA -> Feature Engineering -> Model Building and Selection -> Model Evaluation -> Business Impact -> End
Executive Summary
This analysis provides a comprehensive exploration of Amazon product reviews and related attributes, uncovering insights into product performance, customer preferences, and the impact of pricing and discounts.
________________________________________
Key Insights:
1. Product Categories:
●	Amazon's most abundant product categories (as a percentage of the dataset):
○	Electronics: 525 products (35.9% of total).
○	Computers & Accessories: 453 products (30.9% of total).
○	Home & Kitchen: 448 products (30.6% of total).
________________________________________
2. Impact of Discounts on Ratings:
●	Customer Ratings: Regardless of discount percentage, most ratings fall between 3.5 and 4.5.
●	Discount Analysis: No strong trend suggests that higher discounts consistently improve ratings. This could imply other factors (e.g., product quality or brand reputation) significantly influence customer satisfaction.
________________________________________
3. Top-Rated Categories:
●	Office Products: Highest average rating at 4.31, followed by Toys & Games with 4.30.
●	These categories collectively make up less than 10% of the dataset but have the most satisfied customer base.
________________________________________
4. Correlation Between Price and Ratings:
●	A weak positive correlation (0.11) exists between the actual price and the rating.
○	Interpretation: Higher-priced products may slightly trend toward higher ratings, but this relationship is not strong enough to make broad generalizations.
________________________________________

5. Rating Distribution:
●	Majority of Ratings:
○	Ratings of 4 or higher account for approximately 70% of all ratings, reflecting generally positive customer feedback.
○	Only 5% of products received ratings below 2.5, indicating a relatively small pool of poorly rated products.
________________________________________
Methods and Analysis:
Data Cleaning:
●	Format Adjustments:
○	Removed non-numeric characters (₹, commas) from pricing data.
○	Converted relevant columns to numeric data types to enable computations and statistical analysis.
Statistical and Visual Analysis:
●	Correlations:
○	Studied relationships between key variables (e.g., price, discount percentage, and rating).
●	Visualization:
○	Used bar charts, scatter plots, and heatmaps to interpret and display patterns effectively.
________________________________________
Key Outputs:
●	Dataset Overview:
○	Total Products: 1,465.
○	Attributes Analyzed: 16 (e.g., category, pricing, discounts, ratings, reviews).
●	Category Contribution:
○	Top 3 Categories: Electronics (35.9%), Computers & Accessories (30.9%), Home & Kitchen (30.6%).
________________________________________


Actionable Insights:
1.	Category Focus:
○	Focus marketing efforts on high-performing categories such as "Office Products" and "Toys & Games," where average ratings are notably high.
2.	Price Optimization:
○	Pricing strategies should consider that discounts alone do not guarantee higher ratings; quality and value remain critical factors.
3.	Improving Ratings:
○	Products with lower ratings (5% of the dataset) could benefit from targeted quality improvements or enhanced customer support.
________________________________________
This analysis highlights critical drivers of customer satisfaction and provides actionable insights for improving product performance and marketing strategies on Amazon.

