# DataScienceCompetiton(Stemfellowsip)
This project was created for the data science competition held by Stemfellowship in Canada, where I used 699 samples of benign and malignant breast tumors from Kaggle. The sample contains nine features: mitosis, nuclioli, nulcei, cell size and shape, clump size, adhesion,single epitheloa cell size, and chromatin.

This project is composed of four parts: data collection, data cleaning, visualization of the variables, and creating five machine learning models.

Data Cleaning: After checking Null values, the values have been replaced with mean values since the dataset is small and not categorical. Then the most and least two important features or dependent variables have been identified.

Data Visualization: The relationship between the variables has been explored through craeting violin lpot, heatmap, and pair plot.

![image](https://github.com/AyeshaSKP/DataScineceCompetiton-Stemfellowsip-/assets/41141945/02947a22-c175-4e27-a324-a916f2afc9de)
This fugure has been taken from the paper written by me and my team(BioinfoScience) where we have exlpored the relation betweent two most and least importnat features with and withoutt breast cancer.

Machine Learning Model:
Five types of superivsed machine learning model such as the deep learning with five layers, decison tree, support vector machine, naives bayes and logistic regression have been constructed.
Feature Engineering: Only in case of deep learning, feature engineering has been conducted binary hot encoding has been used to feed the model.

Trainning and Evaluation: Five, six, eight and ten k fold cross validation have been used for k fold cross vlaidation.

Evaluation: ROC plot have been constructed and AUC score, sensitivity, specififivity and accuracy have been calculated.

Total ten model have been created, trained, validated and evaluated where five for all feature and five for two least features.

![image](https://github.com/AyeshaSKP/DataScineceCompetiton-Stemfellowsip-/assets/41141945/12c9123d-07c6-4748-95f4-581e557d210b)
This figure has been taken from the research paper written by BioinfoScience Team at Data Science Competition held by Stemfellowship.

It has been found out that deep learning and SVM with all features and logistic regression with two features have the hightes and lowest AUC scores respectively.

 
