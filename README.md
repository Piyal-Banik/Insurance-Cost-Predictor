
## Insurance Cost Predictor

Create a Machine Learning model which predicts the charges of Insurance

  
## Acknowledgements

 - [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
 

## Author

- [@PiyalBanik](https://twitter.com/PiyalBanik)

  
## Business Understanding
The main goal of this project is to collect and analyze data in order predict the price of insurance. What are the factors that decide the price of an insurance? 


## Analytical Approach: 

Our target variable is Quantitative [take on continuous number], and hence we need regression models for this task.


## Data Requirements:

I needed a dataset that would have various characteristics of an insurance subscriber and the associated charges. 


## Data Collection:

- The dataset is taken from kaggle


## Data Understanding

There are 1338 observations in the training dataset with each having 7 columns. 6 of them are predictor variables and 1 being target variable.
- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- charges: Individual medical costs billed by health insurance


## Modeling & Evaluation

Trained 
- Multiple Linear Regression and received r-squared value of 0.796 
- Polynomial Regression and received r-squared value of 0.884
- RandomForest Regressor and received r-squared value of 0.873
