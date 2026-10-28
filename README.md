# 🏡 House Price Prediction Using Regression

## 📌 Project Overview

This project uses Machine Learning and Linear Regression to predict median house values using the California Housing dataset. It explores the relationship between housing features and house prices and compares Simple Linear Regression with Multiple Linear Regression.

## 🎯 Objectives

- Understand and implement Simple Linear Regression.
- Implement Multiple Linear Regression using multiple features.
- Split data into training and testing sets.
- Evaluate model performance using MAE, MSE, RMSE, and R² Score.
- Visualize actual vs. predicted house values.

## 📊 Dataset

The project uses the **California Housing dataset**, available through Scikit-learn.

It contains information about housing districts in California, including:

- Median income
- Median house age
- Average number of rooms
- Average number of bedrooms
- Population
- Average occupancy
- Latitude and longitude

**Target variable:** `MedHouseVal` — median house value, measured in units of $100,000.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## 🤖 Machine Learning Models

### 1. Simple Linear Regression
Uses median income (`MedInc`) as the input feature to predict median house value.

### 2. Multiple Linear Regression
Uses all eight available input features to predict median house value.

## 📈 Model Evaluation

Both models are evaluated using the following metrics:

| Metric | Purpose |
|---|---|
| MAE | Measures the average absolute prediction error. |
| MSE | Measures the average squared prediction error. |
| RMSE | Measures prediction error in the target's units. |
| R² Score | Measures how much variation in the target is explained by the model. |

The models are compared using their performance on the test dataset.

## 📉 Visualization

The project includes an **Actual vs. Predicted House Values** scatter plot to visualize how closely the predicted values match the actual values.

Points closer to the diagonal reference line indicate more accurate predictions.

## ⚙️ How to Run the Project

1. Clone or download this repository.
2. Open `House_Price_Prediction.ipynb` in Google Colab or Jupyter Notebook.
3. Install the required libraries if they are not already installed:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook cells sequentially.
5. Review the evaluation metrics and visualization.

The dataset is loaded directly through Scikit-learn, so no manual dataset download is required.

## 📁 Project Structure

```text
house-price-prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

## ✅ Conclusion

This project demonstrates how Simple and Multiple Linear Regression can be used for a house-value prediction task. It covers data exploration, model training, evaluation, and visualization while providing practical experience with the basic Machine Learning workflow.

## 👩‍💻 Author

Created as a Machine Learning project for learning and portfolio development.
