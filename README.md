# **Random Forest Regression - Truth or Bluff**  
This project demonstrates the use of **Random Forest Regression** to predict whether a job candidate's salary request is a bluff or true based on their position. Despite the advantage of ensemble learning, **Random Forest** still struggled with small datasets, highlighting the importance of having enough data for the model to generalize effectively.

## **🛠 Technologies Used**  
**Programming Language:** Python  
**Libraries:**  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

## **📊 Project Overview**  
- **Goal:** Predict if a candidate's salary request is a bluff or true based on their position using **Random Forest Regression**.  
- **Dataset:** Contains data with the following features:  
  - Job Position  
  - Salary Requested  

## **🔑 Key Learnings**  
- **Understanding Random Forest Regression:**  
  - **Random Forest** is an ensemble method that builds multiple decision trees and aggregates their predictions to improve accuracy and reduce overfitting.  
  - Despite being more robust than single decision trees, **Random Forest** still struggled with small datasets due to the lack of diversity in data to create multiple meaningful trees.  

- **Data Preprocessing:**  
  - Categorical data (job positions) was encoded using **OneHotEncoder**.  
  - Features were scaled using **StandardScaler** to improve model performance.  

- **Model Training:**  
  - Built and trained the **Random Forest Regression** model using **Scikit-learn**.  
  - Experimented with different numbers of trees (n_estimators) and tree depths to optimize the model.  

- **Visualization:**  
  - Plotted the predictions from the Random Forest and compared them with actual values using **Matplotlib**.  
  - Analyzed the model’s performance and observed that with a small dataset, it didn’t perform as expected, highlighting its limitation in such cases.  

## **🚀 Results**  
- The **Random Forest Regression** model showed similar issues as Decision Trees, with overfitting and poor generalization due to the small dataset.  
- The model could not effectively predict the truth or bluff of salary requests, as the dataset was not large enough to create reliable predictions.  
- Reinforced the importance of having a larger dataset for ensemble methods like **Random Forest**, and showed how small datasets can limit model performance.
