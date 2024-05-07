# Data_science_portfolio
A collection showcasing my journey in data science academic projects, self-learning initiatives, and passion-driven explorations. Dive into the world of data insights through R markdown files and through Jupyter notebooks .


#  Ontario Libraries Insights:
## Introduction

In the 21st century, Ontario libraries are faced with the challenge of ensuring successfully achieving their mission of equity of access to information and contributing to education, literacy, and life-long learning in their communities. In this analysis, the standardized metric to compare Ontario libraries' equality of access is operating revenue per active card holder. This analysis aims to gain three insights around this metric and use the findings to give recommendations to improve Ontario libraries in the future.  

The number of active card holders is an important factor in measuring the equity of access.
The first insight underscores instances where libraries exhibit an absence of active cardholders. The second finding highlights libraries in which the growth rate of active cardholders does not align with the corresponding growth rate of operating revenue. As Electronic materials an important resource of digital information in the 21st, the last insight reveals the increase of the metric and the corresponding increase in number of the electronic materials (e_material) and number of E_circulations.  


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


  


Logistic Regression:
# Titanic Logistic Regression Model

This repository contains the code and analysis for applying a logistic regression model to the Titanic dataset.

## Files

- Titanic_Logistic_Regression.RMD : R Markdown file containing the code, analysis, and results.
- "https://www.kaggle.com/code/daodao32/logistic-regression-for-titanic-dataset/input?select=gender_submission.csv": The Titanic dataset used in the analysis.

## Usage

To reproduce the analysis:

1. Open `Titanic_Logistic_Regression.RMD` in RStudio or your preferred R environment.
2. Run the code chunks to execute the logistic regression model and generate results.
3. Explore the analysis and results within the R Markdown document.

Feel free to fork this repository or use the code for your own projects.

## Results

You can view the rendered R Markdown 
## Notes

- Make sure to have the necessary R packages installed (specified in the R Markdown file).
