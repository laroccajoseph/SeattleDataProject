# SeattleDataProject

The following project was invisioned as a way to analyze the Seattle AirBnb data set provided to us by Udacity & Kaggle, pose 3 business questions in order to make the best use of our data, and then provide the answer to these three questions. The Python notebook is the result of the project.
I have only provided 1 of the 3 data sets used here due to size constrainsts, the rest can be found at: https://www.kaggle.com/airbnb/seattle

The questions I have posed in this analysis are: 

 1. How does one being a "SuperHost" affect the response and acceptance rates? If one is to act as AirBnB, they should understand what value exists for them in having SuperHosts. Are they intrinsically more valuable? They are, then AirBnB should focus on pleasing them and continuing to encourage them to host. If not, AirBnb will not have to placate demanding hosts, and can focus more on pleasing the consumer rather than the client.

 2. What is the relationship between the zipcodes of Seattle and its respective prices? Are there certain areas of the city that are higher priced and AirBnB should focus more so on advertising for, because more people will want to stay there and thus create additional revenues for the company?

 3. What is the overall relationship between the different factors of the AirBnb reviewing system? Is there a point in the way they divide up the reviews or do more often than not the reviews fall in line with the average? Assuming higher reviews lead to an increase in the number of times a place is rented out, it is to AirBnb's advantage to inflate the reviews however they can as Netflix has done in the past in order to drive an better perception of the brand. Can we do this here?

B

Finally, the libraries needed to run this project are the following:

import seaborn as sns
import types
import pandas as pd
from botocore.client import Config
import ibm_boto3
from matplotlib import pyplot as plt
import sklearn
from sklearn.metrics import confusion_matrix

