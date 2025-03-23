# Legendary Pokemon Prediction

## Problem Statement

> The goal of this project is to predict whether a Pokémon is legendary based on its attributes, such as type and stats. 
Legendary Pokémon are rare and powerful creatures, but there are no clear criteria to define them. They are typically identified through information from official media, like games and the anime.

We aim to analyze the available data to understand the factors that may contribute to a Pokémon being legendary and build a predictive model that can classify Pokémon as legendary or not.

## Contents

1. **Introduction:** Background on Pokémon and the project's objective.
2. **Dataset Description:** Overview of the Pokemon dataset used for the analysis.
3. **Exploratory Data Analysis (EDA):** Steps taken to explore and understand the data.
4. **Model Building:** Process of building a predictive model to classify Pokémon as legendary or not.
5. **Model Accuracy:** Evaluation metrics to assess the model's performance.
6. **Conclusion:** Summary of findings and insights derived from the project.
7. **Technologies Used:** List of tools and libraries employed in the project.
8. **Acknowledgement:** Recognition of any resources, individuals, or libraries that have contributed to the project.
9. **Contributor:** Information about the author or team involved in the project.

## About the Dataset

The dataset used in this project contains information about 721 Pokémon. Each Pokémon includes:

* **Number:** Unique identifier for each Pokémon.
* **Name:** The Pokémon's name.
* **Type1:** The primary type of the Pokémon.
* **Type2:** The secondary type of the Pokémon (if applicable).
* **HP:** Hit Points (health) of the Pokémon.
* **Attack:** The Pokémon's attacking power.
* **Defense:** The Pokémon's defensive power.
* **Special Attack:** The Pokémon's special attacking power.
* **Special Defense:** The Pokémon's special defensive power.
* **Speed:** The Pokémon's speed.
* **Legendary:** Whether the Pokémon is legendary (True/False).


## Strategy

The strategy involves exploring the dataset through EDA, identifying potential features related to legendary status, and building a classification model to predict legendary status based on these features. A decision tree algorithm was chosen for this predictive task.

## Exploratory Data Analysis (EDA) Steps

1. **Data Loading and Inspection:** Load the dataset into a pandas dataframe and inspect the data.
2. **Data Cleaning:** Handling missing values and irrelevant columns if necessary.
3. **Feature Engineering:** Transforming categorical variables to numerical variables using Label encoding.
4. **Correlation Analysis:** Exploring the correlation between features and the target variable (Legendary).
5. **Visualization:** Using visualizations (e.g., heatmaps) to better understand the relationships between variables.

## Model Building Steps

1. **Data Split:** Dividing the dataset into training and testing sets.
2. **Model Selection:** Choosing a Decision Tree Classifier as the model.
3. **Model Training:** Training the Decision Tree Classifier using the training dataset.
4. **Hyperparameter Tuning:** Finding the optimal parameters (like max_depth) for the decision tree to improve accuracy.

## Model Accuracy

The model achieved an accuracy of approximately [insert the model accuracy value]. 
The code provides a dataframe that shows the accuracy of the model based on different values of max_depth for the decision tree.


## Conclusion

The project demonstrated the feasibility of predicting a Pokemon's legendary status based on features like type and stats. The analysis provided insights into the characteristics that contribute to a Pokémon being classified as legendary. Further improvements could be made by exploring different machine learning models and applying more advanced feature engineering techniques.


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Acknowledgement

The project utilized publically available Pokémon dataset. 

## Contributor

[Anirudha Kumar Sahu](https://github.com/anirudhasahu92)
