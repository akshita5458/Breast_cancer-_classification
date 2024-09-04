## Breast_Cancer_Classification ##
This project focuses on building a machine learning model to classify whether a person is cancerous (malignant) or not (benign) based on their medical data. The classification is performed using a Logistic Regression model, and the entire process includes data preprocessing, model training, evaluation, and deployment through a web interface built with Streamlit. Additionally, the web application includes an HTML interface styled with Bootstrap to ensure a responsive and user-friendly experience.


![Screenshot 2024-09-04 193900](https://github.com/user-attachments/assets/a4601314-0fd4-47e1-a395-7103d8d16bbc)
![image](https://github.com/user-attachments/assets/ae45a00f-b8a3-4dc7-98ce-98922796054c)

## Key Components ##

 ***Data Preparation***
 
 
       1.Data Cleaning: The dataset is processed to handle any missing values and outliers.
 
 
       2.Feature Engineering: Medical features related to breast cancer are used to build a more predictive model.
 
 
 
       3.One-Hot Encoding: Categorical variables are encoded into numerical format using One-Hot Encoding for compatibility with the Logistic Regression model.
 

 
      4.Standardization: Features are scaled using StandardScaler to ensure they have a mean of 0 and a standard deviation of 1, which helps in improving the 
                          performance of the Logistic Regression model.

 
 
 **Machine Learning Model** 

 
 
    1.Logistic Regression: A supervised learning algorithm used for binary classification. In this case, it predicts whether a tumor is malignant or benign based 
                           on input features.


    2. Model Evaluation

   
    3.Metrics: The model's performance is evaluated using several metrics including accuracy, precision, recall, F1-score, and AUC-ROC, which are computed using 
               the sklearn.metrics module.


     4.Visualization: Tools like Seaborn and Matplotlib are used for visualizing the data distribution, model performance, and feature importance.



**Web Application**


    Streamlit: Used to create an interactive web application where users can input their medical data and get predictions on whether they might have breast cancer.
    
    HTML & Bootstrap: The web interface is designed using HTML for structure and Bootstrap for styling, making the application visually appealing and responsive.
    
    Pickle: The trained Logistic Regression model is saved using Pickle, allowing it to be loaded into the Streamlit application for real-time predictions.
    

