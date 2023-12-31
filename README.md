# DataScienceCompetiton(Stemfellowsip)
This project was created for the data science competition held by Stemfellowship in Canada, where I used 699 samples of benign and malignant breast tumors from Kaggle. The sample contains nine features: mitosis, nuclioli, nulcei, cell size and shape, clump size, adhesion,single epitheloa cell size, and chromatin.

This project is composed of four parts: data collection, data cleaning, visualization of the variables, and creating five machine learning models.

Data Cleaning: After checking Null values, the values have been replaced with mean values since the dataset is small and not categorical. Then the most and least two important features or dependent variables have been identified.

Data Visualization: The relationship between the variables has been explored through craeting violin plot, heatmap, and pair plot.

![image](https://github.com/AyeshaSKP/DataScienceCompetiton-Stemfellowsip-/assets/41141945/e9d59981-064f-4e4b-8cdf-a936d3c904ff)


 This figure  has been taken from the paper written by me and my team (BioinfoScience), where we have explored the relationship between the two most and least important features with and without breast cancer.

![image](https://github.com/AyeshaSKP/DataScienceCompetiton-Stemfellowsip-/assets/41141945/a1cd74c8-a72a-432f-b27c-f9668589504a)

 The above figure has been taken from the research paper related to this data science competition written by me and my team.


Machine learning model:
Five types of supervised machine learning models, such as deep learning with five layers, decision trees, support vector machine, naive bayes, and logistic regression, have been constructed.
Feature Engineering: Only in the case of deep learning has feature engineering been conducted where binary hot encoding has been used to feed the model.

Trainning and Evaluation: Five, six, eight and ten k fold cross validation have been used for k fold cross vlaidation.

Evaluation: ROC plot have been constructed and AUC score, sensitivity, specififivity and accuracy have been calculated.

Total ten model have been created, trained, validated and evaluated where five for all feature and five for two least features.

![image](https://github.com/AyeshaSKP/DataScienceCompetiton-Stemfellowsip-/assets/41141945/bf4a4283-6c13-4a5d-8c83-c5188c34844a)

This figure has been taken from the research paper written by BioinfoScience Team at Data Science Competition held by Stemfellowship.

It has been found out that deep learning and SVM with all features and logistic regression with two features have the hightes and lowest AUC scores respectively.

 
