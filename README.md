# Prediction-Survival-on-the-Titanic
Given a dataset of a subset of the Titanic's passengers predict whether they will survive or not.

# PROJECT TITLE
The Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making it one of the deadliest commercial peacetime maritime disasters in modern history.
We are asked to predict whether a passenger on the titanic would have been survived or not.

# GETTING STARTED
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites
You just need Python 3.0+ or Jupyter Notebook installed in your local machine or you can open the project in Google Colab.

Install Python: https://www.python.org/downloads/

Install Jupyter Notebook:- https://jupyter.org/install.html

For Google Colab:- Just type Google Colab in any Search Engine and click on the Google Colab link(Upload Image and Code File in Your Google Drive Account and make sure the Path is correct according to your account where you have Uploaded)

# Algorithm Used:-

1. Random Forest:- is a supervised learning algorithm. Like you can already see from it’s name, it creates a forest and makes it somehow random. The „forest“ it builds, is an ensemble of Decision Trees, most of the time trained with the “bagging” method. The general idea of the bagging method is that a combination of learning models increases the overall result.
To say it in simple words: Random forest builds multiple decision trees and merges them together to get a more accurate and stable prediction.
One big advantage of random forest is, that it can be used for both classification and regression problems, which form the majority of current machine learning systems. 

2. Logistic Regression:- uses an equation as the representation, very much like linear regression and used for Prediction. Input values (x) are combined linearly using weights or coefficient values (referred to as the Greek capital letter Beta) to predict an output value (y). A key difference from linear regression is that the output value being modeled is a binary values (0 or 1) rather than a numeric value. 
Below is an example logistic regression equation:
                                               y = e^(b0 + b1*x) / (1 + e^(b0 + b1*x))

# Result
After Comparing the above two Algorithms, we can clearly see that the Random forest Regressor is giving a Accuracy of 98%+ , whereas Logistic Regression is giving a quite low accuracy  89%+ as compared to Random Forest Regressor.

# Improvement
Of course there is still room for improvement, like doing a more extensive feature engineering, by comparing and plotting the features against each other and identifying and removing the noisy features.

# Contributors
https://github.com/dhruvie/Prediction-Survival-on-the-Titanic/graphs/contributors
