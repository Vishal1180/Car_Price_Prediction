# Car_Price_Prediction
End to End project based on RandomForestRegressor
This project mainly focuses on the predicting the price of your car for resell purpose
The dataset used is car data set available here https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv
The Notebook file is divided into following parts 
1] Importing Necessary Librabries
2] Loading Dataset
3] Exploratory Data analysis  
    Checking and Handling missing values 
    Droping useless columns from dataset
    Selecting catogorial columns converting them using pandas get dumies method
    Finding corelation between columns
    ploting corelation using heatmap
4] Model selection
   Selecting dependent and independent variables
   Using RandomForestRegressor to build model
   Calculating Accuracy
   Finally finding MAE MSE RMSE
5] Creating pickel file used for deployment
6] Deploy the code using herokuapp 
final project is avilable at https://vishcarpriceprediction.herokuapp.com/
