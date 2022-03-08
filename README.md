# Time-Series-Forecasting-Ailerons-data-set
Created Time Series Forecasting (using Weather_data.csv) and Ailerons data set (using ailerons.csv) and also use Docker containers.

## Model number 1-

File name- Time_Series_ForeCasting.ipynb \
Colab Book- https://colab.research.google.com/drive/1MZGOQCAhMaj1HoM-bnEJMoET2UBAM-jP \
Dataset- Weather_data.csv \
Problem statement- \
i) Predict the temperature column ‘ _tempm’ for Delhi, using Time Series Forecasting \
ii) Share your understanding of underlying data using descriptive analytics (You’re encouraged to do data cleaning as well) \
iii) For prediction, try multiple available techniques and choose the best performing model \
iv) Does a time series model developed using deep learning techniques give more accurate predictions? \
v) Model must take a date as input and output the probable temperature for that day (so basically forecast to the given date and then report the value of that date) \
vi) You are allowed to use the other accompanying features as input as well and create a multi-variate forecasting model. \
vii) The training data is available from Jan 1996 - Nov 2016. We will use data from Dec 2016 - April 2017 to check the model accuracy/validity. \

## Model number 2-

File name- Ailerons_data_set.ipynb \
Colab Book- https://colab.research.google.com/drive/15_lC-fVq1RCO31R30V9R2lJ3boA5-PYX \
Dataset- ailerons.csv \
Problem statement- \
This data set addresses a control problem, namely flying a F16 aircraft. The attributes describe the status of the airplane, while the goal is to predict the control action on the ailerons of the aircraft. \
i) Proper EDA and Statistical analysis of data followed by Developing a model, to predict the column “Goal”. \
ii) Loss function is “RMSE”. \
iii) You are encouraged to try out different techniques from ML/DL and share comparative results. \
iv) Use of proper feature selection process and hyperparameter tuning (if required) is necessary. \
v) You’re allowed to do any feature engineering/feature selection you deem necessary. \
vi) Properly commenting the code is required. \

The idea is to do a quick and easy build of a Docker container with a simple machine learning models and run it. In order to start building a Docker container for a machine learning model, let’s consider five files:

    Dockerfile
    Weather_data.csv
    Time_Series_ForeCasting.ipynb
    ailerons.csv
    Ailerons_data_set.ipynb
