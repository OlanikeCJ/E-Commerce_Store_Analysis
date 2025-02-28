# E-Commerce_Store_Analysis
![dashboard](https://github.com/OlanikeCJ/E-Commerce_Store_Analysis/blob/main/Images%20-%20Women's%20Ecommerce/dashboard.png?raw=true)

## Project Overview

In this project, I provided insights into customer reviews from a women's clothing e-commerce store. The dataset includes 23,486 reviews with variables such as ratings, recommendations, feedback counts, and product categories. The analysis aims to uncover patterns in customer preferences and satisfaction.

## Data Cleaning Process

To ensure data accuracy and consistency, the following preprocessing steps were performed:

> * Removed Unwanted Columns: I dropped columns that were not necessary for the analysis.

> * Handled Missing Data: I replaced empty values with "No Data" to maintain consistency.

> * Changed Data Types: I adjusted column types where necessary to ensure proper calculations.

> * Renamed Columns: changed some column names for clarity.

> * Created New Columns: I also introduced an "Age Category" column to group customers into "Young Adults," "Middle-Aged Adults," and "Elderly."

A snapshot of the cleaned data has been included below:

![cleaned](https://github.com/OlanikeCJ/E-Commerce_Store_Analysis/blob/main/Images%20-%20Women's%20Ecommerce/cleaned_data.png?raw=true)

## Calculations

Click [DAX](https://github.com/OlanikeCJ/E-Commerce_Store_Analysis/blob/main/DAX%20Measures) to find simple DAX measures used to calculate key metrics.


## Key Insights

### 1. Class Distribution by Recommendation
- Dresses received the highest number of recommendations.
- Chemises had the lowest recommendation count, with no recommendations at all.

### 2. Positive Feedback by Division
- The "General" division had the highest positive feedback (60%), followed by "General Petite" (35%) and "Intimates" (5%).

### 3. Positive Feedback by Age Category
- Middle-aged adults provided the highest number of positive feedback (26,361), followed by young adults (25,180) and elderly customers (8,018). 
- Elderly customers had the least positive feedback, indicating lower engagement or satisfaction.

### 4. Recommendation by Age Category
- Young adults had the highest number of recommendations, followed by middle-aged adults.
- Elderly customers had the lowest recommendation rates.

### 5. Top 5 Rated Product Classes
- The "Sleep" class had the highest average rating (4.29).
- The "Trend" class had the lowest average rating (3.82).

## Business Recommendations based on Analysis

1. **Leverage High-Performing Categories**
   - Dresses and sleepwear receive high recommendations and ratings. The company should promote these categories more aggressively in marketing campaigns.

2. **Improve Underperforming Product Classes**
   - Classes like "Trend" and "Chemises" received lower ratings and recommendations. The company should investigate potential quality or design issues and improve these products.

3. **Engage Elderly Customers**
   - Since elderly customers provide fewer recommendations and positive feedback, the business could come up with targeted engagement strategies such as personalized promotions or usability improvements to enhance their experience.

4. **Optimize Marketing by Age Group**
   - Young adults are the most likely to recommend products. The company should focus influencer campaigns, social media engagement, and targeted promotions on this segment.

5. **Enhance Customer Experience in Low-Feedback Divisions**
   - The "Intimates" division received the least positive feedback, partly because there are fewer products/reviews in this division compared to the others. The company should investigate product quality, customer concerns, or marketing gaps within this category to increase purchase levels.

6. **Encourage More Reviews**
   - Given that feedback plays a role in influencing new customers, the company should incentivize more customers to leave reviews, especially for underperforming categories.

## Conclusion
This analysis highlights key trends in customer satisfaction and product performance. By leveraging high-performing categories, addressing weaker segments, and optimizing engagement strategies, the company can enhance customer experience and drive more sales.



