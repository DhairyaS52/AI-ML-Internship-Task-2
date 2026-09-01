# Task 2 - Exploratory Data Analysis (EDA)

## About the Project

This project is part of my AI & ML Internship. For this task, I worked on Exploratory Data Analysis (EDA) using the Titanic dataset.

The main aim was to understand the data, check for missing values and outliers, and find some useful patterns using statistics and graphs.

## Dataset

I used the Titanic dataset for this task.

Some of the columns in the dataset are:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Fare
* Cabin
* Embarked

## What I Did

In the notebook, I performed the following:

* Loaded and checked the dataset
* Checked the number of rows and columns
* Checked data types
* Checked missing values
* Checked duplicate records
* Generated summary statistics
* Filled missing values in Age and Embarked
* Created histograms for numerical features
* Created boxplots to look for outliers
* Compared survival based on gender
* Compared survival based on passenger class
* Created a pairplot
* Created a correlation matrix and heatmap
* Checked skewness
* Detected outliers using the IQR method

## Some Observations

From the analysis, I found that:

* There are missing values in some columns, especially Cabin and Age.
* Fare has a right-skewed distribution and contains some high-value outliers.
* Female passengers had a higher survival rate than male passengers.
* First-class passengers had a better survival rate compared to lower classes.
* Passenger class and fare are related, as first-class passengers generally paid higher fares.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Files

* `ElevateLabs_Task2_EDA_Titanic.ipynb` - Google Colab notebook containing the analysis
* `titanic.csv` - Dataset used for the analysis
* `README.md` - Project details

## Conclusion

EDA helped me understand the Titanic dataset better and identify things like missing values, outliers, skewness and relationships between different features.

This analysis also gives a better idea of what needs to be considered before using the dataset for a machine learning model.

## Internship

**AI & ML Internship - Task 2**
