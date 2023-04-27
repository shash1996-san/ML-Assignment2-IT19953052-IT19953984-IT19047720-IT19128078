# Predict the quality of white wine using machine learning 

**Code Analysis**
This code reads a dataset on white wine quality from the UCI machine learning database and performs exploratory data analysis (EDA) and modeling tasks.

Firstly, the dataset is loaded and displayed, including the first few rows of the data, histograms of each column, and a count of instances for each quality class. Then, a correlation matrix and heatmap are created, as well as a scatter plot of quality and alcohol. After confirming there are no missing values in the quality column, the data is split into training and testing sets, and the features and target variables are defined. The data is then normalized using StandardScaler. Four models are trained and evaluated: linear regression, logistic regression, random forest classifier, and SVM classifier. For each model, the accuracy score, precision score, recall score, F1 score, confusion matrix, and classification report are computed and printed.

**Output Analysis**
The output starts by showing the first five rows of the dataset, which include columns for fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and quality. The histograms show the distribution of each column, which ranges from 0 to 1 for most columns, except for residual sugar, free sulfur dioxide, and total sulfur dioxide, which have a wider range. The count of instances for each quality class shows that most wines have a quality score of 6, followed by 5 and 7.

The correlation matrix and heatmap show that alcohol has the highest correlation with quality. The scatter plot confirms this finding, showing that as alcohol increases, quality tends to increase as well.
