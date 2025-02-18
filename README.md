# Titanic-Survival-Prediction-Using-Logistic-Regression-and-Data-Preprocessing
This project focuses on predicting survival on the Titanic using machine learning techniques. The dataset was preprocessed, handling missing values, encoding categorical data, and scaling features. A Logistic Regression model was built, trained, and evaluated to predict passenger survival.
**Dataset**
Train Data: Contains features such as passenger demographics, ticket information, and survival status.
Test Data: Contains similar features as the training data, but without the survival column. This dataset is used to make predictions.
**Columns in Dataset:**
PassengerId: Unique identifier for each passenger.
Survived: Target column indicating whether the passenger survived (1) or not (0).
Pclass: Passenger's class (1, 2, 3).
Name: Name of the passenger.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard the Titanic.
Parch: Number of parents/children aboard the Titanic.
Ticket: Ticket number.
Fare: Passenger fare.
Cabin: Cabin number.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
**Project Structure**
**train.csv**: Training dataset with passenger information and survival status.
**test.csv**: Test dataset for making survival predictions.
titanic_classification.ipynb: Jupyter notebook where the project is implemented, including data preprocessing, model building, and evaluation.
predictions.csv: File containing predicted survival outcomes for the test dataset.
**Libraries Used**
pandas
numpy
scikit-learn
matplotlib
seaborn
**Steps to Run the Project**
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/titanic-survival-prediction.git
**Install the necessary libraries:**
bash
Copy
Edit
pip install -r requirements.txt
Run the titanic_classification.ipynb notebook to preprocess the data, train the Logistic Regression model, and generate predictions.
**Conclusion**
This project demonstrates the application of machine learning for a classification problem using the Titanic dataset. Data preprocessing steps like handling missing values, encoding, and scaling were applied, followed by building a Logistic Regression model to predict passenger survival.

**Notes:**
Replace your-username with your actual GitHub username.
If you created a requirements.txt file, list the libraries you used.
Update the project structure section with any files that you have in the project.

