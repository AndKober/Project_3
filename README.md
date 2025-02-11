# **Hotel Rating Prediction – Kaggle Competition**  

 **Kaggle Competition Link:** [Hotel Rating Prediction](https://www.kaggle.com/competitions/sf-booking/)  

## **Table of Contents**  
1. [Project Overview](#project-overview)  
2. [Business Problem](#business-problem)  
3. [Dataset](#dataset)  
4. [Feature Engineering & Data Preprocessing](#feature-engineering--data-preprocessing)  
5. [Model & Results](#model--results)  
6. [Key Insights & Conclusion](#key-insights--conclusion)  

## **Project Overview**  
This project is part of a Kaggle competition focused on **predicting hotel ratings** based on user reviews and hotel attributes.  
The primary goal is **to develop an effective data preprocessing pipeline** and apply feature engineering techniques to improve prediction accuracy.  

## **Business Problem**  
Understanding hotel ratings is crucial for both **hoteliers and travelers**. A reliable rating prediction model can:  
- Help hotels improve customer satisfaction by identifying key review factors.  
- Assist users in making informed booking decisions.  
- Detect potential rating fraud or manipulation.  

## **Dataset**  
The dataset includes information about hotels, customer reviews, and additional metadata.  
It consists of **16 features**, including **text reviews, geolocation data, and booking details**.  

## **Feature Engineering & Data Preprocessing**  
Key steps in data transformation:  
- **Handling missing values**: Reconstructed hotel coordinates using external sources.  
- **Text Processing**: Used **SentimentIntensityAnalyzer** to extract sentiment scores from reviews.  
- **Feature Extraction**: Generated numerical features from categorical data (e.g., travel type, review length).  
- **Multicollinearity Analysis**: Identified and addressed redundant features.  

## **Model & Results**  
- **Model used**: RandomForestRegressor (as per Kaggle competition rules).  
- **Evaluation Metric**: Mean Absolute Percentage Error (MAPE).  
- **Final MAPE Score**: **12.23%**, ranking in the **top 100** submissions.  

## **Key Insights & Conclusion**  
- Feature engineering significantly improved model performance.  
- Sentiment analysis of reviews provided valuable insights into customer opinions.  
- The final model achieved **competitive accuracy**, demonstrating the effectiveness of advanced data preprocessing techniques.  
