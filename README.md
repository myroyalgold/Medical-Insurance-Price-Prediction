# Medical-Insurance-Price-Prediction
Performed data analytics on a medical insurance charges dataaset with Python Programming Language


# Objectives
- Load the data as a pandas dataframe
- Clean the data, taking care of the blank entries
- Run exploratory data analysis and identify the attributes that most affect the charges
- Develop single variable and multi variable Linear Regression models for predicting the charges
- Use Ridge regression to refine the performance of Linear regression models.

# Setup
We will be using the following libraries:
- pandas for managing the data.
- numpy for mathematical operations.
- sklearn for machine learning and machine-learning-pipeline related functions.
- seaborn for visualizing the data.
- matplotlib for additional plotting tools.

  
# Parameters
The parameters used in the dataset are:

Age: Age of the insured (Integer).

Gender: Gender of the insured, mapped to numerical values:

| Gender | Assigned Value |
|--------|----------------|
| Female | 1              |
| Male   | 2              |

BMI: Body Mass Index of the insured (Float).

No_of_Children: Number of children the insured person has (Integer).

Smoker: Smoking status, mapped to numerical values:

| Smoker       | Assigned Value |
|--------------|----------------|
| Smoker       | 1              |
| Non-smoker   | 2              |

Region: Region of the USA, mapped to numerical values:

| Region    | Assigned Value |
|-----------|----------------|
| Northwest | 1              |
| Northeast | 2              |
| Southwest | 3              |
| Southeast | 4              |

Charges: Charges for the insurance in USD (Float).

# Tasks:
- Import the dataset
- Data Wrangling
- Performed Exploratory Data Analysis (EDA)
- Model Development
- Model Refinement
