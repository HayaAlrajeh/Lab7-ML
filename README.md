## Logistic Regression Assignment

### Overview

In this project, a Logistic Regression model was developed to predict whether a user is likely to click on an advertisement based on a set of input features.

---

### Dataset

The dataset used in this assignment is advertising.csv, which contains the following features:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male
* Clicked on Ad (Target)

---

### Steps

#### 1. Exploratory Data Analysis

The dataset was initially explored by performing the following:

* Importing and loading the dataset using pandas
* Displaying sample rows with the head() function
* Inspecting dataset structure using info()
* Analyzing summary statistics with describe()

---

#### 2. Visualization

Different visualization techniques were applied to better understand the data:

* Histogram to observe the distribution of age
* Jointplots to study relationships between variables
* KDE plot to examine data density
* Pairplot to visualize interactions between features and the target variable

---

#### 3. Data Preparation

Before training the model, the following steps were completed:

* Identifying the independent variables (features)
* Defining the dependent variable (target)
* Splitting the dataset into:

  * Training set (70%)
  * Testing set (30%)

---

#### 4. Model Building

The model was created using Logistic Regression from the sklearn library, and then trained on the training dataset.

---

#### 5. Evaluation

Model performance was assessed by:

* Generating predictions on the test dataset
* Using the following evaluation metrics:

  * Classification Report
  * Confusion Matrix
  * Accuracy Score

---

### Results

The model achieved an accuracy of approximately 0.96 (96%), which reflects strong performance in predicting user behavior.

---

### Conclusion

The dataset was effectively analyzed, and a Logistic Regression model was successfully built. The model showed good performance on the test data and demonstrated reliable predictive ability.

---

### Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
