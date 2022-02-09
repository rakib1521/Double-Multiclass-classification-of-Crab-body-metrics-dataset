# Multiclass classification of Crab body metrics dataset


This dataset has 200 rows and 8 columns, describing 5 morphological measurements on 50 crabs each of two color forms and both sexes, of the species Leptograpsus variegatus collected at Fremantle, W. Australia.

Species:
Blue
Orange 
Sex :
Male 
Female 

The main purpose of this experiment is to predict both Species and sex using a Multiclass classification problem.

In this project, I will use two methods.

## Method 1:

I created a new column using species and sex column, and then I trained a machine learning model(MLP) and predict both species and sex of the given value also calculated the time required for this task. 

## Method 2:

I trained three models, the first model was used to predict Male / Female, and then the model used another model to predict species.


## Dataset preparation: 
For train purposes, I used 80% of the dataset, and 20% of data is used for the test.
In the training K-fold validation is used.

## Result:

Confusion matrix of method one: 


Confusion matrix of method two detecting male or female: 


Confusion matrix of method two detecting Blue or orange of male dataset: 


Confusion matrix of method two detecting Blue or orange of female dataset: 



The time used for method one was 

The time used for method two was 

