# maleal2-Assignment_4_1_for_Module_4_in_AAI_530_Data_Analytics_and_the_Internet_of_Things_MariaLealCardenas02042024
Assignment 4.1: Long Short Term Memory Networks for IoT Prediction - USD

# Household Electric Consumption Dataset. 
This assignment is a part of the AAI-530 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). 
Assignment Status: [Completed]

## Installation
To use this project, first clone the repo on your device using the below command:
git clone https://github.com/maleal2/Assignment-3.1-Linear-Regression-for-IoT.git

## Project Introduction
This dataset contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months).
Notes: 
1.(global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.
2.The dataset contains some missing values in the measurements (nearly 1,25% of the rows). All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.

## Contributors
1.	Maria Carolina Leal Cardenas
   
## Methods Used
1. Basic Data cleaning inspection.
2. Long Short Term Memory RNNs ( Recurral Neural Networks ). 
3. Long Short Term Memory with Sequal layers.
4. Mean Squared Error ( MSE ).
5. R-2 squared. 

## Technologies
   Python
   
## Project Description
Data source: (https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumptio)
Name of the variables: Date	Time,	Global_active_power	,Global_reactive_power	,Voltage	Global_intensity	,Sub_metering_1	,Sub_metering_2, and	Sub_metering_3.

Number of variables: 9

Size of the dataset:  2075259 

Used Descriptive Analysis, Long Short Term Memory RRNs. 

## Acknowledgments
Thank you Professor An Tran and Professor Anna Marbut for your excellent  class. 
