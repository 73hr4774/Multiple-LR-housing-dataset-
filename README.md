# House Price Prediction

This project uses a linear regression model to predict house prices based on various features.

## Dataset

The dataset used for this project contains information about houses, including:

* **area:** The area of the house in square feet.
* **bedrooms:** The number of bedrooms in the house.
* **bathrooms:** The number of bathrooms in the house.
* **stories:** The number of stories in the house.
* **parking:** The number of parking spaces available.
* **mainroad:** Whether the house is located on a main road (yes/no).
* **guestroom:** Whether the house has a guest room (yes/no).
* **basement:** Whether the house has a basement (yes/no).
* **hotwaterheating:** Whether the house has hot water heating (yes/no).
* **airconditioning:** Whether the house has air conditioning (yes/no).
* **prefarea:** Whether the house is located in a preferred area (yes/no).
* **furnishingstatus:** The furnishing status of the house (furnished/semi-furnished/unfurnished).
* **price:** The price of the house.

## Model

A linear regression model is used to predict the price of a house based on its features. The model is trained on a portion of the dataset and evaluated on the remaining portion.

## Evaluation

The model's performance is evaluated using the mean squared error (MSE) and the R-squared value. The MSE measures the average squared difference between the predicted and actual house prices. The R-squared value measures the proportion of the variance in the house prices that is explained by the model.

## Usage

To use the model, you can provide the values for the features of a house, and the model will predict the price of the house.

## Visualization
-A scatter plot is used to visualize the actual vs. predicted house prices.

## Conclusion

This project demonstrates how to use a linear regression model to predict house prices. The model achieves a reasonable level of accuracy, as indicated by the MSE and R-squared values. Further improvements could be made by exploring different model architectures or by incorporating additional features into the dataset.
