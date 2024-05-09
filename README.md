# Data_science_portfolio
A collection showcasing my journey in data science academic projects, self-learning initiatives, and passion-driven explorations. Dive into the world of data insights through R markdown files and through Jupyter notebooks .

Projects in this folder are:
1. Ontario Libraries Insights.
2.  Simple Linear Regression.
3. Titanic Logistic Regression Model.
4. SVM Support Vector Machine Classification to classify zoo data


#  1. Ontario Libraries Insights:
## Introduction

In the 21st century, Ontario libraries are faced with the challenge of ensuring successfully achieving their mission of equity of access to information and contributing to education, literacy, and life-long learning in their communities. In this analysis, the standardized metric to compare Ontario libraries' equality of access is operating revenue per active card holder. This analysis aims to gain three insights around this metric and use the findings to give recommendations to improve Ontario libraries in the future.  

The number of active card holders is an important factor in measuring the equity of access.
The first insight underscores instances where libraries exhibit an absence of active cardholders. The second finding highlights libraries in which the growth rate of active cardholders does not align with the corresponding growth rate of operating revenue. As Electronic materials an important resource of digital information in the 21st, the last insight reveals the increase of the metric and the corresponding increase in number of the electronic materials (e_material) and number of E_circulations.  

R Programming language was used to ingest and clean data, analyze it to uncover insights and lastly, communicate those insights.

## Data selection 

The data is from Ontario Public Library statistics. The data is self-reported data from approximately 380 public libraries, First Nation public libraries and contracting organizations. The data comes in CSV and xlsx format.   

In this project, the selected data is from the survey years in the range of 2015 to 2022.
The measured data selected (columns) for this project are:  
*  "A1.14  No. of Active Library Cardholders" 
*  "B2.9  Total Operating Revenues"  
*  "G1.1.2.W  All circulation for E-books, downloadable audio books, music and video"  
*  'B4.01.1  General (Include all physical items that are not electronic, e.g. books, periodicals, etc.)' [^note]  
* "B4.01.2  Electronic (e.g. electronic subscriptions and other databases, downloadable media, gaming  software, Playaway, DVDs, and e-resources)"[^note]  
*"P1.1  Resident Population Served"  
  
The categorical data selected (columns) for this project are:   
* "Library Full Name"  
* "Library Number"  
* "Survey Year From"   
* "A1.10 City/Town"  
  



### Assumptions:  

Assume that historical data for Ontario libraries is accurate and sufficiently comprehensive for analysis. 

Assume each library serves a different number of active card holders, which can be a proxy to the area that they service and its population.

Assume that the standardized metric to compare libraries across Ontario is operating revenue per active card holder. 

# Recommended Actions:

Based on these three insights, to improve the equality of access (total operating revenue / active cardholder) over Ontario libraries, the following actions are recommended:

Further analysis is necessary to understand the expenditures associated with the operating revenue for libraries that exhibit an absence of active cardholders.

Increase the operating revenue for libraries that demonstrate a misalignment between the increasing rate of active cardholders and the increasing rate of operating revenues.


Additional analysis is required to comprehend the wide variety and extreme values of operating revenue/active cardholder, to ensure equality of access.

Invest more in Electronic materials as an important resource of digital information in the 21st century to evolve the users needs and technological advancements.


# 2. Simple Linear Regression:
Title: Applying Simple Linear Regression to Salary Dataset

## Introduction:

In this project, I applied simple linear regression to a salary dataset to explore the relationship between years of experience and salary. The dataset contains 30 observations with two columns: Years of Experience and Salary. I utilized the linear regression model to analyze and visualize the relationship between these variables.

## Dataset:

The dataset used for this analysis can be accessed from Kaggle: https://www.kaggle.com/code/iamravi1/salary-data/input
Methodology:

   1. Data Preparation: I started by loading the dataset and exploring its structure and summary statistics to gain insights into the data.
   2. Data Visualization: Next, I created visualizations such as scatter plots to visualize the relationship between years of experience and salary.
   3. Train-Test Split: Before building the linear regression model, I split the dataset into training and testing sets. This allows for the evaluation of the model's performance on unseen data.
   4. Linear Regression Model: Using the lm() function in R, I fitted a simple linear regression model to predict salary based on years of experience.
   5. Model Analysis: I analyzed the coefficients of the linear regression model to understand the relationship between the predictor and the response variable. 
   Additionally, I evaluated the model's performance using metrics such as RMSE.

## Results:

The linear regression analysis revealed a significant positive relationship between years of experience and salary. 
The coefficient of the predictor variable (years of experience) was found to be 9152.3 , indicating that, on average, for each additional year of experience, the salary increased by 9152.3 units.

The model achieved a Root Mean Square Error (RMSE) of 7686.788, suggesting that the model's predictions were 7686.788.
Conclusion:

In conclusion, the simple linear regression analysis provided insights into the relationship between years of experience and salary. 
The results suggest that years of experience have a significant impact on salary, with higher experience generally associated with higher salaries. 
This analysis can be valuable for organizations in making decisions related to employee compensation and career growth.

  


Logistic Regression:
# 3.Titanic Survival Prediction

This code is to build a logistic regression model to predict survival in the Titanic dataset. The analysis is conducted in R using an R Markdown (Rmd) file.
Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including features such as age, sex, ticket class, and whether or not they survived the sinking of the ship.
Workflow

  ## Data Preparation:
  The dataset is loaded and preprocessed. Missing values are handled, and relevant features are selected for modeling.

  ## Model Building: 
  Logistic regression models are built to predict survival. The dataset is divided into training and validation sets. Two models are trained using different sets of features.

  ## Model Evaluation:
  Both models are evaluated using the validation set. Performance metrics such as accuracy are calculated to assess the models' predictive power.

  ## Model Selection: 
  The model with the highest accuracy on the validation set is selected for further analysis.

  ## Model Application:
  The selected model is then applied to new data to predict survival probabilities.

## Files

    titanic_survival_prediction.Rmd: The R Markdown file containing the analysis code, including data preprocessing, model building, evaluation, and application.
    titanic.csv: The Titanic dataset used in the analysis.

## Usage

To reproduce the analysis:

    Clone this repository to your local machine.
    Open titanic_survival_prediction.Rmd in RStudio or any other R Markdown-compatible editor.
    Run the code chunks sequentially to reproduce the analysis step by step.
    Explore the results and modify the code as needed.

## Result
The selected logistic regression model achieved an accuracy of 78.85% on the validation set, demonstrating its predictive ability in determining survival on the Titanic.


# 4.SVM Classification for Animal Classification

This  contains an RMD code that utilizes Support Vector Machine (SVM) classification to predict the classification of animals based on various traits described in the dataset.
Dataset Description

The dataset used for this project consists of 101 animals from a zoo, with 16 variables describing different traits of the animals. The dataset includes information on 7 class types: Mammal, Bird, Reptile, Fish, Amphibian, Bug, and Invertebrate.

Two files are included in the dataset:

    Zoo.csv: Contains attribute information for each animal.
    Class.csv: Describes the dataset, including class numbers, class types, and the list of animals in each class.

## Dataset Source:
Kaggle – SVM Classification: https://www.kaggle.com/code/sriharshabs/svm-classification/data

## Instructions
To use the SVM classification for animal classification:

    Download or clone the repository to your local machine.
    Ensure you have R installed. If not, download and install it from the official R website.
    Install required packages by running install.packages(c("e1071", "caret")) in your R environment.
    Open the R script svm_classification.R provided in the repository.
    Modify the script as needed or run it directly to predict animal classifications.
    Ensure the Zoo.csv and Class.csv files are in the same directory as the script or provide the correct paths to these files within the script.
    Execute the script in your R environment.

## Usage

The SVM classification code performs the following tasks:

    Data loading and preprocessing.
    Training the SVM model using the provided dataset.
    Evaluating the model's performance.
    Predicting animal classifications based on the input variables.

## Result:
The model was able to classify all the animals correctly except one in class 3 which represent Reptile , resulting in an accuracy of 96.43%. 


Feel free to explore and modify the script according to your requirements.
License

This project is licensed under the MIT License.


