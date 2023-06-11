# Machine-Learning-Pipelines-with-Azure-ML-Studio

Project Description : Using freely available datasets from UCI Machine learning repository on Adult census, I have tried to create a Machine Learning Model, that will predict how much is the income of a dataset. Using independent features like race, sex, age, capital loss, hours-per-week, native country, and others, I bionomically categories any individual if he falls above >=50k income pool, or <50k income pool. I do pre-processing on the available open dataset, do feature engineering, transform the label datatype, and use Decision Tree classifier to train the model , further the final result is deployed as web service.

Problem Statement : Often, financial institutions need to categorize their customers based on their income, however, generic features like age, work-sector, education, are not enough to predict their income. The Adult Census dataset available in UCI ML repository, uses 14 features to predict an individual's income, thus helping in binomial classification of individuals based on their income. The result is useful in accurate service recommendation. Individuals with >= 50k income fall in medium wage income and thus can be segmented to respective promotional services, while those with < 50k income, can be provided with low cost services. Those above >=50k income are eligible for expensive offers and promotional memberships for clubs, credit cards, etc. while those with income <50k, shall be targeted with more budget constrained offers. The categorization can also help in predicting the life-style of the individual.

The project is done in 6 steps:

-Introduction Dataset cleaning and Pre-processing 
-Accounting for class imbalance 
-Training the ML model- Two-Class Boosted Decision tree
-Hyper parameter tuning Scoring and Evaluating the models
-Publishing the trained model as a Web Service

The aim of this project is to build an end-to-end Machine Learning (ML here after) project using the Azure Machine Learning Studio Visual interface which is a no-code platform.

Dataset discussion:

The dataset provided to us contains 32560 rows and 14 different independent features. We are trying to
predict whether a person will earn more than $50,000 a year or not. Since the data predicts 2 values
(>50K or andlt;=50K), this is clearly a classification problem and we train the classification models to
predict the desired outputs.


![DATA CLEANING AND ACCOUNTING FOR CLASS IMBALANCE](https://github.com/richasingh-92/Machine-Learning-Pipelines-with-Azure-ML-Studio/assets/91095253/25836284-1d8a-4d3e-83bd-23728094983c)
![TRAINING TO MODELS](https://github.com/richasingh-92/Machine-Learning-Pipelines-with-Azure-ML-Studio/assets/91095253/aa9fbd14-3855-4565-aecb-f23c4b1d8d26)
![Training a Two-Class Boosted Decision Tree Model](https://github.com/richasingh-92/Machine-Learning-Pipelines-with-Azure-ML-Studio/assets/91095253/c15e42ab-fc4d-4b3c-b283-ef2932261dc5)
![Scoring and Evaluating the Models](https://github.com/richasingh-92/Machine-Learning-Pipelines-with-Azure-ML-Studio/assets/91095253/ed9c0f2c-bc6d-4f07-88b5-1a80478439e7)
![Publishing the Trained Model as a Web Service for Inference](https://github.com/richasingh-92/Machine-Learning-Pipelines-with-Azure-ML-Studio/assets/91095253/068c2a87-0baa-46ba-9fce-01961c265577)







