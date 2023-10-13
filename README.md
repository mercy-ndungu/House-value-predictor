# House-value-predictor
This project is helping compare the between Random Forests and Regression models in predicting house prices.
The dataset used contains various features related to house attributeswhich are:
            1. House size
            2. Number of bedrooms       
            3. Number of bathrooms      
            4. Presence of a waterfront      
            5. Number of views           
            6. the condition of the house     
            7. THe year the house was built      
            8. The year the house was last renovated
 To run the code in this repository you can follow the steps below:
1. Clone the repository
   
```git clone https://github.com/your-username/house-price-prediction.git```

3. 2. Open the Jupyter Notebook in your preferred environment (e.g., Google Colab).

4. Ensure you have the necessary libraries and dependencies installed, such as `pandas`, `numpy`, `scikit-learn`, `seaborn`, and `matplotlib`.

5. Execute the code cells in the Jupyter Notebook to perform data preprocessing, visualization, and model training and evaluation.


 


## Code Overview

Data Preprocessing:
The project begins with importing the dataset, dropping unnecessary columns, handling missing values, and converting data types.

Data Visualization:
Visualizations are used to explore the data, including price distribution, count plots for categorical variables, and box plots for numeric features.

Outlier Detection:
Outliers are identified using Z-scores, and a new dataset is created without outliers.

Correlation Analysis:
The correlations between numeric variables are visualized in a heatmap to understand feature relationships.

Modeling:
Linear Regression and Random Forest Regression models are trained on the data to predict house prices.

Model Evaluation:
Model performance is evaluated using Mean Squared Error (MSE) and R-squared (R2) scores.



## Results

- Linear Regression Model:
  - Mean Squared Error (MSE): 34530973639.27
  - R-squared (R2): 0.52

- Random Forest Regression Model:
  - Mean Squared Error (MSE): 50268525187.06
  - R-squared (R2): 0.31


