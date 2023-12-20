# Black Friday Dataset EDA and Feature Engineering

## Problem Statement
A retail company, "ABC Private Limited," wants to understand customer purchase behavior, specifically the purchase amount, against various products of different categories. The goal is to build a model that predicts the purchase amount based on customer demographics and product details.

## Dataset
The dataset contains purchase summaries of various customers for selected high-volume products from the last month. It includes customer demographics (age, gender, marital status, city type, stay in the current city), product details (product_id and product category), and total purchase amount from the last month.

### Data Cleaning and Preprocessing
- Removed the 'User_ID' column.
- Converted categorical values to numerical values.
- Fixed the 'Age' column by mapping age ranges to numerical values.
- Handled city categorical values using one-hot encoding.
- Fixed missing values in 'Product_Category_2' and 'Product_Category_3' using the mode.
- Processed the 'Stay_In_Current_City_Years' column to remove the '+' sign.
- Converted 'Stay_In_Current_City_Years' to the integer data type.
- Explored and visualized the data using pair plots.

### Feature Scaling
Performed feature scaling using StandardScaler on the training and test datasets.

## Linear Regression Model
Used a Linear Regression model to predict the purchase amount.
Evaluated the model using mean squared error (MSE) and R-squared (R2) score.

## Results
- Mean Squared Error (MSE): [Insert MSE value here]
- R-squared (R2) Score: [Insert R2 score here]

## Conclusion
Summarize the key findings and insights from the exploratory data analysis, feature engineering, and model evaluation. Discuss potential next steps or improvements for the model.

## Dependencies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage
Clone the repository and run the Jupyter Notebook to explore the dataset, perform feature engineering, and train the Linear Regression model.

```bash
pip install -r requirements.txt
