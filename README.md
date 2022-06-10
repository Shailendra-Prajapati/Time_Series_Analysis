## Time_Series_Analysis-Using-LSTM-and-Classical-Models
The aim of this project is to construct an Intelligent System to analyze and predict the stock movement using LSTM and other Classical Models. This project will be focused on implementing Regression techniques (Classical/Neural Network) for the purpose of pattern analysis that reveals the relation between tweets and stock market prices along with the prediction of stock prices in succeeding time.
Data used can be accessed from: https://www.kaggle.com/raavisoni/stocks

Financial Market 'Historical Time Series Data' have been used to predict and analyse the model.
Top 10 Toronto Stock Exchange(TSX) values from January 2016 to April 2020 dataset from Kaggle is being used.
### Data Pre-Processing for Classical Method:
Dataset split into 70%-30% training and testing data. Open,High, Low and Close are used and rest are dropped.

### Data Pre-Processing for ANN :
Sorted Dataset based on Dates.Features - Low, High, Open and Close. 70% Training Data and 30% Testing Data

### Data Pr-Processing for Recurrent Neural Network: 
For Long Short-Term Memory(LSTM), Feature- Low, Open, High and Volume were trained. 70% training set and 30% testing set. 'MinMaxScaler' Normalizer  used to normalize teh dataset

### Model Prediction
Machine Learning and Deep Learning technikques are identified as the primary approach for all predictive learning problems. 
A) Artificial Neural Network
B) Recurrent Neural Network
C) Classical Methods(KNN< LASSO, RIDGE, Random Forest, SVM)

