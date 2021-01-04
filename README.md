# Web Phishing Detection
Phishing attack is used to steal confidential information of a user. Fraud websites appears like genuine websites with the logo and graphics of genuine website. This project aims to detect fraud or phishing website using machine learning techniques.

## Data Selection
The dataset is downloaded from UCI machine learning repository.A collection of website URLs for 11000 websites. Each sample has 30 website parameters and a class label identifying it as a phishing website or not (1 or -1).

## Models & Training
Before stating the ML model training, the data is split into 60-40 i.e., 6600 training samples & 4400 testing samples. From the dataset, it is clear that this is a supervised machine learning task. <br/> <br/>
This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are: <br/> <br/>
- Logistic Regression <br/>
- K-Nearest Neighbour  <br/>
- Decision Tree Classifier  <br/>
- Support Vector Machine <br/>
- Adaboost <br/>
- XGBoost  <br/>

## Accuracy  
![imageonline-co-stackedbarchart](https://user-images.githubusercontent.com/73738015/102687445-25272180-4215-11eb-83ba-260e92bbfa18.png)

## End Results
From all the models we developed,
- Highest accuracy score - 96.5% using Random forest method
- Lowest accuract score - 91.4% using Adaboost method
 
