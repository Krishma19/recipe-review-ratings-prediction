# Recipe Review Ratings Prediction

## Overview
This project focused on building an end‑to‑end machine learning pipeline to predict recipe review star ratings from 1 to 5 using a real‑world review dataset. It covers data cleaning, exploratory analysis, feature engineering from text and categorical fields, and training and evaluating classification models such as Logistic Regression and Random Forest. Key techniques include handling messy data, engineering text‑based features for example, length, sentiment, and punctuation, encoding categorical variables like region and device type, and addressing class imbalance with class weights and detailed evaluation metrics.

## Key Learning
Gained experience designing a full workflow: importing raw recipe reviews, cleaning and preparing the data, exploring it with visualizations, and building models.
Learned how to detect and fix real‑world data issues such as placeholder values used for missing data, duplicate records, inconsistent categories, and incorrect data types.
Discovered that simple NLP‑style features like review length, word count, sentiment score, exclamation marks, capitalization patterns can significantly improve rating predictions.
Practiced handling imbalanced multi‑class data by using class weights and by looking beyond accuracy to precision, recall, F1, and confusion matrices for each star level.
Understood the trade‑offs between interpretable models like Logistic Regression and more flexible ensemble methods like Random Forest in terms of performance and explainability

## Insights
The analysis showed that what people write in their reviews matters a lot for the rating they give.
Longer, more detailed reviews with clearly positive wording tended to receive higher star ratings, while short or negative comments were more common for low ratings.
Sentiment polarity extracted from the review text aligned strongly with star scores: high positive sentiment usually mapped to 4–5 stars, negative sentiment to 1–2 stars.
Differences across regions and device types suggested that user context, such as where and how people submit reviews, can influence how strictly they rate recipes.
Feature‑importance analysis highlighted text‑based features and encoded categorical variables as the main drivers of the predictions, confirming the value of thoughtful feature engineering.
Evaluation plots including confusion matrices, ROC curves, and precision–recall curves showed that mid-range ratings such as 3 stars were harder to predict than very high or very low ratings.

## Impacts
This project demonstrates a practical template for building rating‑prediction systems that could be adapted to other domains like product or app reviews. 
The findings can help platforms highlight more informative reviews, surface experienced reviewers, and provide quick sentiment summaries to support better user decisions. 
By explicitly dealing with class imbalance and evaluating models with richer metrics and visual diagnostics, the workflow also encourages more responsible modeling practices that treat all rating levels more fairly. 
Overall, the project provides a solid foundation that could be extended with more advanced NLP methods or integrated into a larger recommendation or decision‑support system.
