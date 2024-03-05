# Clustering_and_Classification_using_ML_Models
The code conducts exploratory data analysis, preprocessing, model training, and evaluation using various machine learning algorithms on the California housing dataset

Importing Libraries: The code begins by importing necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn modules for data manipulation, visualization, and machine learning algorithms.

Reading Data: It reads the California housing dataset from a CSV file and displays the first few rows to understand the structure of the data.

Data Preprocessing: The code drops irrelevant columns and handles missing values by replacing them with the mean of the respective column. It also converts categorical variables into categorical data types.

Visualizations: Various visualizations are created to explore the relationships between different features and the target variable ('price_category'). Histograms are plotted to visualize the distribution of each feature.

Data Scaling and Splitting: The dataset is split into training, validation, and test sets. The features are scaled using StandardScaler, and oversampling is applied to the training data using RandomOverSampler to handle class imbalance.

Clustering using kNN: The code trains a k-nearest neighbors classifier on the training data and evaluates its performance on the test set using classification metrics such as precision, recall, and F1-score.

Assigning Labels to the DataFrame: The predicted labels are added to the DataFrame containing the test data, and the DataFrame is saved to a CSV file.

Train and Test on Other Machine Learning Models: The code also trains and evaluates the performance of other machine learning models such as Gaussian Naive Bayes, Logistic Regression, and Support Vector Machine (SVM) on the same dataset.

Predicting New Data: Finally, the trained SVM model is used to predict the label for new data, and the predicted label is displayed.
