# Beauty-Product-Rating-Predictor

## Project Overview
This project develops an interactive analytics and prediction tool using Sephora beauty product data. The application performs exploratory data analysis and visualizations to examine pricing trends and product performance across categories. The project also includes a machine learning model that predicts whether a product is likely to be highly rated based on features such as price, brand and category. A Tkinter GUI allows users to explore the dataset and generate rating predictions interactively.

The project was completed as part of the Programming Languages and Techniques course at the University of Pennsylvania.

## Project Motivation
Sephora is one of the largest cosmetic retailers, offering a wide variety of beauty and skincare products. With the large number of products available, it can be difficult for customers to search through reviews and ratings individually when making purchasing decisions.

This project aims to simplify the shopping process by helping users identify products that are likely to receive high ratings based on different features. Through data analysis and predictive modeling, the application makes product discovery more efficient and improves the overall shopping experience.

## Data Source
Cosmetic and skincare product data scraped from Sephora.

The dataset includes product features such as:
- Brand
- Category
- Product name
- Rating
- Number of reviews
- Marketing-related information
- Selling channels
- and other relevant product attributes relevant

## Key Findings
- Random Forest outperformed Logistic Regression, achieving approximately 80.9% accuracy when predicting products rated 4.0 stars or higher, demonstrating the effectiveness of non-linear relationships in rating prediction.
- For the more challenging threshold of 4.2 stars or higher, model performance declined (Random Forest ~62.1% accuracy), suggesting that distinguishing top-rated products is significantly more difficult than identifying generally well-rated products.
- Number of reviews and love count emerged as the strongest predictors of product ratings, indicating that customer engagement and product popularity are highly associated with higher ratings.
- Brand and product category contributed to prediction performance but had less consistent influence compared to popularity-based features.
- Results suggest that consumer ratings are driven more by market traction and customer engagement signals than by brand identity alone.
- Developed an interactive Python application that allows users to evaluate products based on predicted rating likelihood, demonstrating the practical application of machine learning for consumer decision support.
