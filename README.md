# Machine-Learnings-Project
## Part 1: Importing Libraries and Loading the Data
In this section, we import all the required libraries and load the dataset to begin our analysis.
## Part 2: Encoding Categorical Variables
In this section, we use one-hot encoding to transform the 'Extracurricular Activities' column into numerical values.
## Part 3: Visualization
##Part4: Analyzing Feature Correlation with Performance Index
 we sort and display the correlation of each feature with the 'Performance Index' to identify the most influential variables
 ## Exploratory Data Analysis (EDA)
We perform data inspection
check for missing values
and explore the structure of the dataset. 
Visual tools like scatter plots, histograms, and heatmaps 
help us understand relationships between variables and identify patterns or outliers.
## Simple Linear Regression Model
In this part, we use the simple linear regression model we previously trained to predict the Performance Index for a student who scored 80 in Previous Scores.
## Multiple Linear Regression Model
We now use Multiple Linear Regression Model to model the relationship between the Performance Index and all other features in the dataset. This allows the model to learn from multiple variables rather than just one (like in simple linear regression).
## Polynomial Regression
In this part, we explore Polynomial Regression for different polynomial degrees (2, 3, 4).
By increasing the degree, we can fit more complex curves to the data and see how the model's performance changes.
# Summary of Findings:


##Dataset and Preprocessing:

Label Encoding: gender and Status columns were encoded to numeric values.

Ordinal Encoding: The Grade column was converted to numerical values.

One-Hot Encoding: Categorical features like Histological type and Treatment were one-hot encoded.

Standardization: Features were standardized using StandardScaler.


#E Model:

Logistic Regression was used for classification after splitting the data into training (80%) and testing (20%) sets.

The model was evaluated with a confusion matrix and classification report.

#E Results:

Accuracy: 74%

Precision: The model is most accurate for class 0 (NED), but struggles with class 1 (AWD).

Recall: Class 1 (AWD) had the lowest recall (0.58), indicating some misclassifications in this group.

In summary, the model performs fairly well but could benefit from further optimization, especially for predicting the AWD class.
