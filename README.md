# Calorie Predictor

## Project Overview

This project aims to predict whether a food item is high in calories based on its nutritional information. It uses machine learning techniques to build a classification model that identifies high-calorie foods. The model is built using Python, with a focus on data cleaning, imputation, visualization, and classification.

## Features of the Project

- **Data Imputation**: Missing values were handled using advanced imputation techniques, such as filling in missing values based on neighboring data points.
  
- **Data Visualization**: Visualizations were created to explore the dataset and identify trends in the relationship between calorie content and macronutrient levels.
  
- **Machine Learning**: Logistic Regression was used to classify foods as high or low calorie based on their nutritional content. Model accuracy, confusion matrix, and coefficient analysis were included to evaluate model performance.

## Technologies Used

- **Python**: Primary programming language for data processing and model development.
- **Pandas**: Data manipulation and cleaning.
- **scikit-learn**: Machine learning algorithms and evaluation metrics.
- **Matplotlib & Seaborn**: Data visualization libraries for creating static plots.
- **Altair/Plotly (Optional)**: Can be used for interactive visualizations.

## Project Files

- **calorie_predictor.ipynb**: Jupyter notebook containing all code for data cleaning, visualization, and model training.

## Instructions to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook calorie_predictor.ipynb
   ```

## Results

The logistic regression model achieved an overall accuracy of **98.36%**, with high-calorie foods being identified correctly most of the time. Improvements were made through data imputation and feature engineering.

## Future Work

- **Try additional models**: Implement models like Random Forest, SVM, or XGBoost and compare their performance.
- **Hyperparameter tuning**: Use GridSearchCV to find the optimal hyperparameters for the models.
- **Feature engineering**: Explore additional features that could improve the model's performance.

## Conclusion

This project showcases the end-to-end process of building a machine learning model, from data cleaning and imputation to model evaluation and visualization. It highlights skills in **data preprocessing**, **visualization**, and **classification** using logistic regression.