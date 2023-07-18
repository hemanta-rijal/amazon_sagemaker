# amazon_sagemaker
Amazon Sagemaker Implementation

### Steps done in this notebook
#### 1. Import libraries and create s3 bucket
#### 2. Set an output path where train model will saved
#### 3. Set Kaggle API authentication to directly import dataset from Kaggle to notebook
#### 4. Load data and perform analysis 
#### 5. Visualize the data and finding relation between variables
#### 6. Test train split and store the test and trainig data into s3 bucket
#### 7. Build XGBoost container and set hyperparameters
#### 8. Construct a SageMaker estimator that calls the xgboost-container
#### 9. Deploy Machine Learning Model As Endpoints
#### 10. Prediction of the Test Data 
