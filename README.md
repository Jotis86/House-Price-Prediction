# 🏡 House Price Prediction Project

## 🎯 Objective
The objective of this project is to predict house prices based on various features such as average area income, house age, number of rooms, number of bedrooms, and area population. The goal is to build a machine learning model that can accurately estimate the price of a house given these features.

## ⚙️ Functionality
- 📥 Load and clean the dataset.
- 📊 Visualize the data to understand relationships between features.
- 🤖 Build and evaluate a linear regression model.
- 🔮 Predict house prices based on new input values.
- 📈 Provide visualizations to help understand the model's performance.

## 🛠️ Tools Used
- **Python**: Programming language used for data analysis and machine learning.
- **Pandas**: Library for data manipulation and analysis.
- **NumPy**: Library for numerical computations.
- **Matplotlib**: Library for creating static, animated, and interactive visualizations.
- **Seaborn**: Library for statistical data visualization.
- **Scikit-learn**: Library for machine learning.

## 📝 Development Process
1. **Data Loading and Cleaning**:
   - Load the dataset using Pandas.
   - Check for missing values and clean the data.
   - Remove unnecessary columns (e.g., `Address`).

2. **Data Visualization**:
   - Visualize the distribution of house prices.
   - Create a correlation heatmap to understand relationships between features.
   - Generate pair plots, box plots, and regression plots to explore data.

3. **Model Building and Evaluation**:
   - Normalize and scale the data.
   - Split the data into training and testing sets.
   - Build and evaluate a linear regression model.

4. **Prediction**:
   - Create a function to predict house prices based on new input values.
   - Test the model with example input values.

## 📊 Results
- **Linear Regression**:
  - Mean Squared Error: 10,089,009,300.89
  - Mean Absolute Error: 80,879.10
  - R^2 Score: 0.918

## 📈 Visualizations
1. **Distribution of House Prices**:
   !Distribution of House Prices

2. **Correlation Heatmap**:
   !Correlation Heatmap

3. **Pairplot of Features**:
   !Pairplot of Features

4. **Boxplot of House Prices by Number of Bedrooms**:
   !Boxplot of House Prices by Number of Bedrooms

5. **Regression Plots**:
   - House Prices vs. Average Area Income
     !House Prices vs. Average Area Income
   - House Prices vs. House Age
     !House Prices vs. House Age
   - House Prices vs. Area Population
     !House Prices vs. Area Population

6. **Countplot of Number of Bedrooms**:
   !Countplot of Number of Bedrooms

7. **Predictions vs Actual Values**:
   !Predictions vs Actual Values

8. **Residuals Plot**:
   !Residuals Plot

9. **Distribution of Residuals**:
   !Distribution of Residuals

10. **Errors vs Actual Values**:
    !Errors vs Actual Values

11. **Percentage Errors vs Actual Values**:
    !Percentage Errors vs Actual Values

## 🧪 Manual Testing
To manually test the model, you can use the `predict_house_price` function to input new values and get the predicted house price. 

## 📂 Project Structure
- The project is organized as follows:
  - Data
  - Notebook

## 📌 Conclusions
- The Linear Regression model performed well in terms of accuracy and explained variance.
- Visualizations helped in understanding the relationships between features and the target variable.
- Manual testing allows for easy prediction of house prices based on new input values.

## 📞 Contact
- If you have any questions or would like to get in touch, please contact me at: jotaduranbon@gmail.com

