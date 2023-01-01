### Diabetes Predictor Web App  

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg) ![](https://img.shields.io/badge/-hacktober-brightgreen)

#### How the project works  
  - Using the dataset we do EDA and find a suitable model
  - The model turn out to be random forest
  - aplying train test spilt on the dataset
  - Model is fit on training data following eda for observation
  - Then model is fit on out of sample data or testing data
  - In the backend we make a form that accepts parameters from users
  - These parameters are passed in an array
  - The model is pickled and passed to the backend.
  - the pkl model is fit on the array and prediction is rendered to html file.
  - here we put a condition case that if predition is this then render this result.
  - The HTML and CSS files are binded in the backend itself
#### Dependencies
  - ML model ===>>>   Scikit Learn  
  - Backend   ===>>> Flask(Python)  
  - Frontend  ===>>>  HTML & CSS  
  
  
  ---
#### Contributors please read contribution guide before submitting a PR   
   
*Template credits to Anuj Vyas who also deplyed this project on heroku check out his profile for deployment*
