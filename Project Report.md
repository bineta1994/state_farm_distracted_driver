# State Farm Distracted Driver Project Report

## Executive Summary
This report presents the findings and insights from a data science project focused on analyzing the State Farm Claims dataset to improve the claims process and detect potentially fraudulent claims. The project aimed to develop models that could predict the severity of claims and identify distracted driving behavior using both tabular and image data. While the project encountered some limitations and challenges, it provides valuable insights for future improvements in claim assessment and fraud detection.

## Problem Statement and Value
The underlying question of the project was to explore the factors contributing to the severity of claims and detect potentially fraudulent claims. By developing accurate prediction models, the project aimed to enhance the efficiency of the claims assessment process, minimize financial losses due to fraudulent claims, improve customer satisfaction, and promote safe driving practices. The project adds value by providing insights into claim severity and fraud detection, leading to more informed decision-making and improved processes within the insurance industry.

## Background
Distracted driving is a critical issue on roads, causing accidents and fatalities. This project addresses the challenge of identifying distracted driving behavior using machine learning techniques. By leveraging data science, the project seeks to overcome limitations of traditional methods and provide automated analysis for more effective claim assessment and fraud detection.

## Dataset
The State Farm Claims dataset consists of both tabular data and images of drivers in various states of distraction. The tabular data contains three columns, including the target variable, which represents the class of the claim. The image data provides visual information on distracted driving behavior. The dataset was collected by State Farm and aims to improve claim processing and driver safety. It is made available through Kaggle.

## Cleaning and Preprocessing
The data underwent preprocessing to handle missing values, normalize numerical features, and encode categorical variables. Exploratory data analysis (EDA) was conducted to understand the distribution of variables, identify correlations, and gain insights into the data. Feature engineering techniques were applied to extract relevant information from the images, such as identifying key visual cues related to distracted driving.

## Insights, Modeling, and Results
The project employed various machine learning models, including K-Nearest Neighbors (KNN), Logistic Regression, and Decision Trees. The models were trained and evaluated using appropriate metrics, such as accuracy, precision, recall, and F1-score. The results showed that the performance of the models was below the desired level, indicating the need for further improvements. The accuracy, precision, recall, and F1-score values were relatively low, suggesting that the models struggled to accurately classify the positive instances of distracted driving and severity of claims.

## Findings and Conclusions
Based on the analysis and modeling, the project identified several areas for improvement. The limitations in the dataset, such as its size, quality, and representation, affected the models' performance. To enhance the models, acquiring a larger and more diverse dataset, exploring advanced image analysis techniques (e.g., Convolutional Neural Networks), and incorporating additional external features (e.g., weather conditions, driver demographics) could be beneficial. Ensemble techniques and hybrid models may also improve the overall performance. Despite the challenges faced, the project provides valuable insights for future research and development in claim assessment and fraud detection.

In conclusion, the project aimed to analyze the State Farm Claims dataset to improve the claims process and detect potentially fraudulent claims. The results highlighted the need for further enhancements in the models' performance. By addressing the limitations and exploring advanced techniques, the project opens avenues for more accurate claim severity prediction, fraud detection, and improved decision-making in the insurance industry. The practical value of the project lies in its potential to streamline claims processing, reduce fraudulent claims, enhance customer experience, and promote safer driving practices. Future directions include acquiring comprehensive datasets, incorporating advanced image analysis techniques, and considering additional features for more reliable predictions
