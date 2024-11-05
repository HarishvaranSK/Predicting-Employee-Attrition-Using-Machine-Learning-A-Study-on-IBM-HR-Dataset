## Predicting Employee Attrition Using Machine Learning: A Study on IBM HR Dataset

## Project Overview
This project aims to predict employee attrition using machine learning techniques, focusing on the application of Principal Component Analysis (PCA) and hyperparameter tuning. The dataset contains various features related to employee demographics, job roles, and performance metrics, enabling the development of predictive models.

## Features
- Predictive modeling for employee attrition.
- Utilizes PCA for dimensionality reduction.
- Implements hyperparameter tuning for improved model performance.

## Dataset
The Employee Attrition Dataset is included in the `datasets` directory. It contains both categorical and numerical features related to employee demographics and job performance.

**Dataset Link :** https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset 

## Results
This project successfully explored the impact of Principal Component Analysis (PCA) and hyperparameter tuning on the performance of machine learning models for predicting employee attrition. SVM with the RBF kernel emerged as the best-performing model, achieving the highest accuracy and F1-score. Logistic Regression provided a competitive and more interpretable alternative, while KNN showed decent performance but was less effective in this context.
The objective was to develop a predictive model for employee attrition, which was successfully accomplished with high accuracy (90% using SVM). The challenge of predicting employee attrition was addressed by selecting relevant features, applying PCA for dimensionality reduction, and optimizing models to enhance prediction accuracy. The final outcome is a comprehensive comparison of models, with SVM emerging as the best-performing model for predicting employee attrition.

**Code link:** https://colab.research.google.com/drive/1EX-Pssyxv36zXDxD6cMNlo4gKX_Pu-8b?usp=sharing

## Advantages
**Effective Dimensionality Reduction:** PCA reduced feature complexity while retaining crucial information, aiding in the prevention of overfitting.
**Hyperparameter Optimization:** GridSearchCV ensured that the models operated at their best possible configurations.
**Accurate Predictions:** The project achieved high prediction accuracy, particularly with SVM, making it a viable solution for employee attrition prediction.

## Limitations:
**Model Interpretability:** While SVM provided the highest accuracy, it is less interpretable than Logistic Regression, which could be a limitation in some business contexts.

**Sensitivity to Data:** KNN was highly sensitive to outliers and neighborhood size, which restricted its effectiveness on this dataset.

**Computational Cost:** The hyperparameter tuning process, especially for SVM, was computationally expensive due to the multiple grid searches performed across parameters.

## Project Credits
**Project By:** Harishvaran S K

**Guided By:** Swetha Varadarajan

**Institution:** SASTRA Deemed to be University

**Special Thanks:**

[Kaggle for providing the dataset]

[OpenAI for developing ChatGPT, which assisted in generating ideas and documentation]

## Acknowledgments
I would like to express my gratitude to all the resources, tutorials, and forums that helped me throughout this project.
