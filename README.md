# Car Price Prediction: 95% Accuracy Achieved

![Car Price Distribution](https://i.imgur.com/7NGRv0C.png)

## Overview

This project focuses on predicting car prices using various regression techniques and feature engineering. We achieved a remarkable 95% accuracy in our predictions.

## Dataset

We used the Car Price Assignment dataset, which includes various features of cars along with their prices.

## Exploratory Data Analysis

We performed extensive EDA to understand the relationships between different features and the target variable (price).

![Car Prices by Body Type](https://i.imgur.com/AGI2e8G.png)

![Engine Size vs Horsepower](https://i.imgur.com/zVGnyYD.png)

## Feature Engineering

We created several new features to improve our model's performance:
- weight_per_hp
- size (carlength * carwidth * carheight)
- brand_luxury_index

## Models Used

1. Linear Regression
2. Ridge Regression
3. Lasso Regression

## Results

Our best model achieved an R-squared score of 0.95, indicating excellent predictive power.

![Feature Importance](https://i.imgur.com/MX6wDqD.png)

## Conclusion

Through careful feature engineering and model selection, we were able to create a highly accurate car price prediction model. The engineered features proved to be valuable in improving the model's performance.

## Future Work

- Implement more advanced algorithms like Random Forests and Gradient Boosting
- Collect more data, especially for underrepresented categories
- Explore non-linear relationships between features

## How to Use

1. Clone this repository
2. Install the required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook Car_Price_Prediction.ipynb`

## Author

[Your Name]

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Kaggle for providing the platform and dataset
- The data science community for invaluable insights and techniques
