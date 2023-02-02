Project Title: # Bank-Fixed-Deposit-Prediciton
Project Description: The goal of the model is to predict if the client will subscribe a term deposit (variable y).
The target variable is categorical, hence a classification model has been build

The flow of the case study is as below:
  * Reading the data in python
  * Defining the problem statement
  * Identifying the Target variable
  * Looking at the distribution of Target variable
  * Basic Data exploration
  * Rejecting useless columns
  * Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
  * Feature Selection based on Data Distribution
  * Outlier treatment
  * Missing Values treatment
  * Visual correlation analysis
  * Statistical correlation analysis (Feature Selection)
  * Converting data to numeric for ML
  * Trying multiple classification algorithms
  * Selecting the best Model
 
 Models: Logistic Regression, Decision Tree
 
 # Data Description
Input variables:
   bank client data:
      1 - age (numeric)
      2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
      3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
      4 - education (categorical: "unknown","secondary","primary","tertiary")
      5 - default: has credit in default? (binary: "yes","no")
      6 - balance: average yearly balance, in euros (numeric) 
      7 - housing: has housing loan? (binary: "yes","no")
      8 - loan: has personal loan? (binary: "yes","no")
   
   related with the last contact of the current campaign:
      9 - contact: contact communication type (categorical: "unknown","telephone","cellular") 
      10 - day: last contact day of the month (numeric)
      11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
      12 - duration: last contact duration, in seconds (numeric)
   
   other attributes:
      13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
      14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
      15 - previous: number of contacts performed before this campaign and for this client (numeric)
      16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

  **Output variable (desired target):**
      17 - y - has the client subscribed a term deposit? (binary: "yes","no")
