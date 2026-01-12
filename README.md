This project implements a machine learning model to forecast residential property prices based on various physical and location-based features. Using a dataset of housing records, the model employs multiple linear regression to understand how attributes like area, room count, and furnishing status influence market value.

# House Price Prediction

## Project Overview

The objective of this project is to develop a predictive tool for real estate valuation. It processes property data through an end-to-end machine learning pipeline—from categorical data encoding to model evaluation—achieving a balanced  score that indicates a strong correlation between property features and price.

## Dataset Features

The model analyzes several key attributes to predict property prices:

* **Numerical Features**: Property area, number of bedrooms, bathrooms, stories, and parking spaces.
* **Categorical Features**: Mainroad access, presence of a guestroom or basement, hot water heating, air conditioning, and preferred area status.
* **Property Status**: Furnishing status, categorized as unfurnished, semi-furnished, or furnished.

## Technical Workflow

1. **Data Preprocessing**: Categorical variables are transformed into numerical formats using `OrdinalEncoder` to make them compatible with regression algorithms.
2. **Feature Selection**: The dataset is split into independent features () and the target variable (price, ).
3. **Model Implementation**: A **Multiple Linear Regression** model is trained using a 60/40 train-test split to ensure robust testing on unseen data.
4. **Evaluation Metrics**: The model is assessed using:
* **Mean Absolute Error (MAE)**: ~776,490.
* **Mean Squared Error (MSE)**: ~1,146,848,567,097.
* ** Score**: ~0.676 (67.6% accuracy in variance explanation).



## Technologies Used

* **Python**: Core programming language.
* **Pandas & NumPy**: For data manipulation and array processing.
* **Scikit-Learn**: For the machine learning pipeline, including `OrdinalEncoder`, `train_test_split`, and `LinearRegression`.
* **Plotly**: Utilized for future or supplementary data visualization.

## Usage

To run this project:

1. Ensure you have the `Housing.csv` dataset in the project directory.
2. Install the required dependencies:
```bash
pip install numpy pandas scikit-learn plotly

```


3. Execute the cells in `house_price_prediction.ipynb` to train the model and generate predictions.

---
