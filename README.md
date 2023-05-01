# credit-risk-classification
Using the dataset of the historical lending activity of peer-to-peer lending services company, I built a model that identifies the creditworthiness of borrowers.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
The dataset was split into training and testing sets.  I used the logistic regression model to train the original data to predict if the loan was either healthy or high-risk.  The predictions from the model returned a balanced accuracy score of 95.2% indicating a well performance.  Then I resampled the training data with the RandomOverSampler model.  The resampled data was then used in the logistic regression model for retesting.  At a quick glance, model 2 appears to perform better, but we must always review the overall results and consider the purpose of the training.  This is extremely important and further supports why multiple training models are used to determine which is the most suitable.  The predictions from the resampled data shows an improvement for the high-risk loans.  The balanced accuracy score also increased to 99.3%.  Model 2 would be best if the goal is the check for high-risk loans.  

Checking for both high-risk and healthy loans are equally important.  We may want to determine whether or not approve additional loans to a borrower or if a new process should be implemented, such as additional monitoring or assistance options to mitigate those that are high-risks.  There isn't a one size fit all and we should continue to train with current and new models for improvement. 


## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Sklearn
- Matplotlib                                                                                        


## Screenshots
![1](https://user-images.githubusercontent.com/117790100/235510305-fac80b31-6bfb-4229-b052-a54b689e0c64.png)
![2](https://user-images.githubusercontent.com/117790100/235510307-ed7dd78e-2120-46a5-93dd-4628aee4d27d.png)
![3](https://user-images.githubusercontent.com/117790100/235510308-27092728-61e1-4b9d-9c6e-2637d55e87e6.png)
![4](https://user-images.githubusercontent.com/117790100/235510310-a440eefd-0607-4f30-8d12-917856c7e3e2.png)

## Setup
The dataset used for this project can be found in the Resources folder.  Analysis of the findings is found in report.md.  


## Project Status
Project is complete and no longer being worked on.


## Acknowledgements
- Many thanks to my instructional team and David Chao.


## Contact
Created by Diane Guzman.
