Titanic Dataset Preprocessing Pipeline

This project demonstrates a basic data preprocessing pipeline for the Titanic dataset. It focuses on cleaning the data, handling missing values, encoding categorical variables, and scaling numerical features to prepare the data for machine learning.

Steps Performed:

1. Data Cleaning:

Removed irrelevant columns (PassengerId, Name, Ticket, Cabin).

Filled missing Age values with the median.

Dropped rows with missing Embarked values.



2. Feature Engineering:

Separated the target variable (Survived) from features.

Identified numerical (Age, Fare) and categorical (Pclass, Sex, Embarked) features.



3. Preprocessing:

Scaled numerical features using StandardScaler.

Encoded categorical features using OneHotEncoder.

Combined transformations using ColumnTransformer.



4. Train-Test Split:

Split the dataset into training (80%) and testing (20%) sets.

Applied preprocessing to both sets.



Technologies Used:

Python

Libraries: pandas, scikit-learn



How to Run:

1. Clone this repository:

git clone <repository_url>
cd <repository_folder>


2. Install dependencies:

pip install pandas scikit-learn


3. Run the script to preprocess the Titanic dataset.
