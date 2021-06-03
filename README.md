# Flight-Fare-Prediction-ML

Created a project that estimates Flight Prices to help the end user to look for best prices when booking flight tickets.

Features extraction of this dataset are Departure Time, Date of Journey, to quantify the data and make it more useable.

Built a client using API model with the help of flask framework

## Codes and Resources Used
Python Version: 3.8.5

Packages: pandas, numpy, sklearn, matplotlib, seaborn, flask, pickle

Dataset: https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh

Python IDE: coblab

## Process
Importing Required Package

Data Wrangling/Cleaning

Classification

Prediction 

Calculate Loss and Accuracy

Visualization


## Importing Required Package
![image](https://user-images.githubusercontent.com/74816597/120583619-3626c080-c44c-11eb-8994-f8e251de4698.png)
![image](https://user-images.githubusercontent.com/74816597/120585605-aaaf2e80-c44f-11eb-8171-45d394117e9e.png)


## Data Wrangling/Cleaning
#### Checking whether the dataset is filled with nan value or not.
#### If the dataset have NAN value dropna() function used to drop the na value.


![image](https://user-images.githubusercontent.com/74816597/120583733-6a9a7c80-c44c-11eb-9b18-5f0dd7c9b653.png)


#### Converting Departure_time, Arival_time, Date_of_Journey to datetime datatype


![image](https://user-images.githubusercontent.com/74816597/120584136-04622980-c44d-11eb-90ed-d687fbac1ac6.png)


#### Split all Date_of_Journey to Date and Month
![image](https://user-images.githubusercontent.com/74816597/120585046-b1897180-c44e-11eb-939b-54d50593216a.png)


![Untitled Diagram](https://user-images.githubusercontent.com/74816597/120584933-78e99800-c44e-11eb-9dd1-812510cefcb4.jpg)


![image](https://user-images.githubusercontent.com/74816597/120585206-fca38480-c44e-11eb-9a41-074ba5745eba.png)


![image](https://user-images.githubusercontent.com/74816597/120585247-0b8a3700-c44f-11eb-8207-4c1664c767f1.png)

#### mutual_info_classif() function which is used to calculate the mutual relationship between each column of the dataset. It is help to understand the important features of the dataset. 
![image](https://user-images.githubusercontent.com/74816597/120585652-c1ee1c00-c44f-11eb-8671-5bce8b8ae651.png)

![image](https://user-images.githubusercontent.com/74816597/120585899-31640b80-c450-11eb-905c-f75a4a6287e4.png)


## Classification
#### Spliting the dataset into Test Train and split.
![image](https://user-images.githubusercontent.com/74816597/120586026-6ec89900-c450-11eb-9194-088cde883bab.png)

#### RandomForest
![image](https://user-images.githubusercontent.com/74816597/120586143-9a4b8380-c450-11eb-9177-d1646606e7d3.png)

#### LinearRegression
![image](https://user-images.githubusercontent.com/74816597/120586191-ac2d2680-c450-11eb-805d-a10b950fe64a.png)

#### KNN
![image](https://user-images.githubusercontent.com/74816597/120586568-63c23880-c451-11eb-9354-5f53595324cd.png)

#### Decision Tree
![image](https://user-images.githubusercontent.com/74816597/120587898-d59b8180-c453-11eb-83b4-ff76f896da2b.png)

## Hyperparameter
![image](https://user-images.githubusercontent.com/74816597/120587833-ba307680-c453-11eb-9c00-364db82e235a.png)

## After Hyperparameter
![image](https://user-images.githubusercontent.com/74816597/120588347-a9cccb80-c454-11eb-93e2-c5b9a3f58859.png)

## Accuracy
![image](https://user-images.githubusercontent.com/74816597/120588773-63c43780-c455-11eb-9aa4-d1be7ca2f3d0.png)

## Final Output:
![image](https://user-images.githubusercontent.com/74816597/119849291-224dfc80-bf2a-11eb-9a1c-014244c74773.png)
