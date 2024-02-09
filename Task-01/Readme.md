// The code you provided is a markdown document that describes a project on predicting the survival of
// passengers aboard the Titanic using the Random Forest algorithm. It includes an introduction,
// dataset description, code overview, model training, model evaluation, visualization, results, and
// conclusion. The visualization section describes two graphs that show the survival rates of men and
// women based on different factors. The results indicate the accuracy of the Random Forest model, and
// the conclusion summarizes the effectiveness of the algorithm in predicting survival outcomes.
# Titanic Survival Prediction with Random Forest

## Introduction
This project utilizes machine learning techniques, particularly the Random Forest algorithm, to predict the survival of passengers aboard the Titanic. The sinking of the Titanic is one of the most infamous shipwrecks in history, and this dataset provides valuable information for exploring patterns of survival.

## Dataset
The dataset used in this project is the Titanic dataset, which contains various attributes of passengers such as their age, gender, ticket class, number of siblings/spouses aboard, number of parents/children aboard, fare, cabin, and port of embarkation. The dataset also includes a binary outcome variable indicating whether the passenger survived or not.

## Code Overview
1. **Importing Libraries:** Necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn are imported for data manipulation, visualization, and machine learning modeling.
   
2. **Exploratory Data Analysis (EDA):** The dataset is loaded and explored to understand its structure, data types, and summary statistics. Exploratory visualizations are created to analyze the distribution of variables, identify correlations, and gain insights into potential relationships between features and survival.

3. **Data Preprocessing:** Data preprocessing steps are performed to handle missing values and encode categorical variables. Missing values in the 'Age' column are imputed using the median age, and missing values in the 'Embarked' column are filled with the most frequent value. Categorical variables like 'Sex' and 'Embarked' are converted into numerical representations. Unnecessary columns such as 'PassengerId', 'Name', 'Cabin', and 'Ticket' are dropped from the dataset to improve model performance.

4. **Model Training:** The Random Forest classifier is chosen as the predictive model due to its ability to handle non-linear relationships and feature interactions effectively. The model is trained using the preprocessed dataset, with features as input and the 'Survived' column as the target variable.

5. **Model Evaluation:** The trained model's performance is evaluated using both training and testing datasets. Metrics such as accuracy, precision, recall, and F1-score are computed to assess the model's predictive performance. Additionally, a confusion matrix is generated to visualize the model's true positive, false positive, true negative, and false negative predictions.

6. **Visualization:** The confusion matrix is plotted to provide a graphical representation of the model's performance in predicting survival outcomes. This visualization helps in understanding the model's strengths and weaknesses in classifying passengers as survivors or non-survivors.

## Visualization

From the first grpah i labbled men and women as 1 and 0 respectively and we can see that more than 500 women survived but nearly 350 men were able to survive.
<br />
And in the second graph we can see that women form the class p3 had a higher survival compared to other classes, but for men passengers from p1 class had a higher survival rate.


## Results
The Random Forest model achieves a training accuracy of 97.9% and a testing accuracy of 81.1%. The model demonstrates a relatively high accuracy in predicting survival outcomes based on the provided features.

## Conclusion
The Random Forest algorithm proves to be effective in predicting the survival of passengers aboard the Titanic. By leveraging the dataset's features and applying machine learning techniques, this project contributes to understanding the factors influencing survival during the Titanic disaster.

