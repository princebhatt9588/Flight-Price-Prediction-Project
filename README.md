# Flight Price Prediction

The accurate prediction of flight ticket prices is becoming increasingly crucial for both passengers and airlines. This project's primary objective is to develop a robust model capable of accurately predicting flight prices using historical data. The model will empower passengers to make well-informed decisions regarding the optimal timing to book flights and assist airlines in making more informed pricing decisions.

## Data Source

The project utilizes flight-related data obtained from [Kaggle](). The dataset includes essential details such as flight prices, airlines, departure and arrival times, and other relevant information. The dataset is split into a training set and a test set, allowing the model to undergo training on the former and be subsequently evaluated on the latter.

## Preprocessing Steps

Before building the model, the dataset undergoes essential preprocessing steps to ensure its suitability for accurate predictions. The preprocessing stages encompass the following key procedures:

1. Importing the necessary libraries to facilitate the data manipulation process.
2. Loading the training and test datasets into pandas dataframes for easy manipulation.
3. Combining the training and test datasets into a unified dataframe for comprehensive data analysis.
4. Cleaning and transforming the data to eliminate missing values, irrelevant columns, and converting string values into numeric values.
5. Encoding categorical variables into numerical representations for compatibility with the model.

## Model Development

![imag 1_11541](https://github.com/princebhatt9588/Flight-Price-Prediction-Project/assets/117750531/65922545-bce0-45a5-bd12-11e9efde9821)


The model itself is constructed using the powerful Random Forest Regressor from the scikit-learn library. The model undergoes training using the preprocessed data and is assessed based on performance metrics such as mean squared error and R-squared. The results demonstrate that the model possesses a remarkable ability to predict flight prices with a high degree of accuracy.

## Project Outcomes

This project successfully produces a sophisticated model for flight price prediction, providing an invaluable tool for passengers and airlines alike. Passengers can now make well-informed choices about the most opportune moments to book their flights, while airlines can employ the model to optimize their pricing strategies. The entire codebase of this project is open-source, allowing users to utilize and adapt it according to their specific needs.
