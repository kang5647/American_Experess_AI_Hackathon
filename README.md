# American Express AI Hackathon Project

## Overview
This project was developed for the American Express AI Hackathon, focusing on optimizing merchant recommendations for American Express credit card customers to maximize incremental activations. The challenge involved working with a dataset of approximately 10 million records, featuring both known and unknown variables, to predict which merchant recommendations would be most effective in driving additional customer transactions.

## Problem Statement
The goal was to identify merchants for each customer that would lead to the highest number of incremental activations—transactions that likely wouldn't have occurred without a recommendation. Success was measured by the Incremental Activation Rate, emphasizing the value added by accurately targeted recommendations.

## Approach
Our approach involved several key steps:
- **Data Preprocessing**: Handling a large dataset with 10 million records, managing missing values, and encoding categorical variables.
- **Feature Engineering**: Developing features from both known and unknown variables, leveraging domain knowledge and data analysis.
- **Missing Value Prediction**: Utilizing machine learning algorithms to impute missing values based on observed correlations in the data.
- **Model Development**: Training an autoencoder to understand complex relationships within the data and predict customer behavior in response to merchant recommendations.

## Key Technologies
- **Data Analysis and Preprocessing**: Python, Pandas, NumPy
- **Machine Learning/Deep Learning**: Scikit-learn, PyTorch, Pytorch-tabnet
- **Data Visualization**: Matplotlib, Seaborn

## Results
- Developed a robust model capable of predicting incremental activations with high accuracy.
- Implemented an effective imputation strategy for missing data, improving the model's performance.
- Demonstrated the potential of autoencoders in capturing complex patterns and relationships in large-scale data.

## Challenges Faced
- Managing and processing a large dataset with limited computing resources.
- Identifying meaningful features from unknown variables in the dataset.
- Balancing the trade-off between model complexity and performance.

## Future Work
- Further tuning of the autoencoder architecture to enhance prediction accuracy.
- Exploration of additional feature engineering techniques to better capture customer preferences and behaviors.
- Deployment of the model into a real-world testing environment to validate predictions and refine the recommendation strategy.

## Team Members
- [kang5647](https://github.com/kang5647)
- [ShengZhe0820](https://github.com/ShengZhe0820)


## Acknowledgements
We would like to thank American Express for hosting this challenging and insightful hackathon. Our appreciation also goes to all team members for their dedication and hard work throughout this project.

---
