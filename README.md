# Diabetes-Prediction-Project
Diabetes Prediction model using Logistic Regression
# This is just an AI prediction. Doctor consultation is always recommended. 
This project predicts if a person can have diabetes based on his/her Age, Blood Pressure, Body Mass Index, Plasma Glucose Concentration, Insulin, Pregnancy, Triceps Skin Fold Thickness, Diabetes Pedigree Function. 
This model uses Logictic Regression.
This model is trained on 768 samples from diabetes dataset.

## Performancce
- Log Loss: 0.4908333908615375
- Accuracy: 0.8116883116883117
  
- Confusion Matrix:
 [[92  7]
 [22 33]]

-                 precision  recall   f1-score   support

         0.0       0.81      0.93      0.86        99
         1.0       0.82      0.60      0.69        55

- ROC AUC 0.8246097337006428
## How to see Diabetes Prediction model in action on a website?
1. Open 'Logitic Regression Model' folder.
2. Download 'model_d.pkl' file.
3. Now open Website Code.
4. Open 'Diabetes_Prediction_Website.ipynb' in google colab.
5. Click 'Run all'.
6. Copy IPv4 address from output of second last cell.
7. In the cell you will get this in output'"Need to install the following packages:localtunnel@2.0.2 Ok to proceed? (y)'.
8. Type 'y' and enter.
9. You will get an URL in last cell output with a line 'your url is: __'.
10. Click on that link.
11. You will be redirected to an website.
12. On that website add IPv4 address you copied earlier in 'Tunnel Password' box and submit it.
13. Diabetes Prediction Website will be open.
14. Upload 'model_d.pkl' in 'Drag and drop file here'.
15. Now write the asked data and clcick 'Predict' buttoon.
16. You will get 'Predicted'.
    
## How to view code of Logistic Regression.
1. Open 'Logistic Regression Model' folder.
2. Open 'CSV Dataset' folder.
3. Download 'diabetes.csv'.
4. Now come back to 'Logistic Regression Model' folder.
5. Open 'Diabetes_Prediction.ipynb' in google colab.
6. Upload 'diabetes.csv' in files of  'Diabetes_Prediction.ipynb' in google colab.
7. Click 'Run all'.

## Dataset Source
The dataset is taken from Kaggle.
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data
   
## Dependencies
- Python
- Scikit-learn
- Streamlit
- NumPy
- Pandas
- Matplotlib
- Pickle
  
## License
MIT License
