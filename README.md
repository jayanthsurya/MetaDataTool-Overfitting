Reduce data overfitting in a dataset designed for Mobile Price Prediction Model

Introduction:
This project builds a machine learning model to predict mobile phone prices based on their features like battery capacity, screen size, resolution, camera specs etc. while our main objective here is to identify if the dataset is overfitting and if so regularize it using ridge regression.

Data:
The dataset used is mobi.xlsx which contains details of various mobile phones and their prices.

Libraries Used

pandas
sklearn
LogisticRegression
Ridge
train_test_split
LabelEncoder
StandardScaler
r2_score

Data Preprocessing:
The dataset is loaded into a Pandas dataframe and the unnecessary columns are removed. The categorical features like Operating System, WiFi etc are label encoded. The dataset is split into training and test sets and feature scaling is done using StandardScaler.

Model Training:
A LogisticRegression model is trained on the training data. Ridge regression is also implemented to reduce overfitting.

Model Evaluation:
The R2 score is calculated on both train and test sets. The scores are printed to check for overfitting.

Conclusion:
The model can effectively predict mobile prices based on the provided features. Some overfitting is present which can be reduced using regularization techniques like Ridge.

Next Steps:
Try other models like Random Forest, SVM etc.
Optimize hyperparameters using GridSearch.
Deploy the model to make live predictions.
