## Fraud prediction Shill Bidding - Ebay

## Shill Bidding Detection using Supervised Machine Learning Techniques


### Introduction
It is known that online auctions transactions are getting more and more popular. However, it is difficult to guarantee the safety of customers when they are dealing with dishonest sellers. The intention of this project is to analyze and prepare the Shill_Bidding_Dataset in order to perform different machine learning techniques to predict if a type of fraud known as shill bidding was used. The dataset is available on the UCI machine learning repository and includes over 6000 bids on eBay.

### Data Preparation
#### Characterization of the Dataset
Each row represents a bid, and each column provides information about the bid such as the bidder ID, auction ID, bid time, and bid amount. The column "Class" indicates whether the bid is normal (0) or anomalous (1).

### Data Cleaning and Exploratory Data Analysis
The first step in data preparation is cleaning and EDA. I performed basic cleaning techniques such as renaming columns and removing redundant columns. EDA visualizations were used to identify patterns in the data and to determine the best approach to feature engineering.

### Feature Engineering
Several feature engineering techniques were applied to the dataset including SMOTE, scaling, and splitting. SMOTE was used to address the imbalanced dataset. Scaling was applied to the dataset to normalize the features. Splitting was used to split the data into training and testing sets.

### Dimensionality Reduction
Both LDA and PCA were used to reduce the dimensionality of the dataset. The results of both techniques were compared to determine which method provides better class separation.

### Baseline Model
A baseline model was developed using a Dummy Classifier with default hyperparameters. This model was used to compare the performance of other machine learning models.

### Supervised Machine Learning (Classification models)
Five different supervised machine learning models were used to predict the target variable: SVC, Decision Tree Classifier, Random Forest Classifier, Logistic Regression, KNeighbors Classifier (KNN). The best parameters for each model were determined using GridSearch.

### Model Performance
The performance of each model was evaluated using testing accuracy, precision, and F1 score. The results of each model were compared to determine which model provides the best performance.

### Conclusion
In conclusion, this project demonstrates that supervised machine learning models can be effective in detecting shill bidding in online auctions. LDA and PCA were used to improve the performance of the models. The best performing model was the Random Forest Classifier. Further research could investigate the use of unsupervised machine learning techniques for shill bidding detection.

### Keywords
Shill bidding, data preparation, imbalanced dataset, PCA, LDA, supervised ML, GridSearch, Model Performance
