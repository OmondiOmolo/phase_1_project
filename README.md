# Aviation Data Analysis

**Author**: Shem Omondi

## Overview

The business problem is that the company wants to venture into the Aviation Business but has no prior knowledge of potential risks associated with aircrafts. The data of use which was collected and gathered by the NTSB was then cleaned and analyzed in order to gain insights on the different aircrafts' aviation statistics. Through pandas and its associated libraries, various methods of cleaning, analysis and visualizing the data were employed. As a result, a cleaned version of the dataset along various informative visualizations were created. Various recommendations were then made based on different criteria such as total fatal injuries, total number of accidents and total uninjured people. These recommendations were made considering that the purpose of the flight was for Business.

## Business Problem

The company has ventured into the aviation business. Particularly, operating airplanes for commercial and private enterprise.
The challenge is that the company has no prior knowledge of potential risks associated with the aircrafts.
The aim is to determine which aircrafts bear the least risk to the company as it starts this new business venture.
Aviation data of accidents between the years 1962-2023 by the NTSB was retrieved from Kaggle.
Through the use of this data, the safest aircrafts specific to our purpose can be identified and recommended.

## Data

The data of use will be the cleaned version of the aviation dataset by the NTSB which was retrieved from Kaggle which is an open website containing various datasets.
The data consists of the following relevant features; the aircraft make and model, total fatal injuries, total uninjured people, the purpose of the flight, the accident location, the number of engines and engine type of involved aircrafts.
These features, while considering the purpose of the flight, can help to determine which aircrafts are safest to operate for the commercial and private enterprise venture.

## Methods

A number of methods were used to clean, analyze and visualize the data.
First, through the use of pandas libraries in python, both AviationData.csv and NTSB_Database.csv were loaded into data frames.
Then the duplicated rows were dropped based on the event id column.
The non duplicated rows also contained numerous null values which were replaced by either the mode or mean and in the case of categorical data, an unknown category was used.
The null values in columns such as total uninjured, total minor injuries, total serious injuries were filled as 0. This is because the data showed that if all people involved suffered fatal injuries, then these columns were null.
Finally, the columns with too many missing rows such as latitude and longitude were dropped.
The cleaned version was then merged to the data frame containing information from NTSB_database.csv which appeared to have some relevant columns whose rows were filled.
Some visualizations were also made with the aid of matplotlib.pyplot and seaborn.
This approach enabled us to simplify the data cleaning, analyzing and visualization process especially considering the dataset contains numerous rows and columns.

## Results

### Accident/Incident Occurrence against Engine Type
<img width="1686" height="696" alt="image" src="https://github.com/user-attachments/assets/d721465a-05c1-43f9-bcb8-daa3507cd052" />
### Number of uninjured people against aircraft 
<img width="910" height="815" alt="image" src="https://github.com/user-attachments/assets/1c6e417e-b30a-4686-8162-c2ed5c66708d" />
### Aircraft Category against Total Fatal Injuries
<img width="976" height="649" alt="image" src="https://github.com/user-attachments/assets/88e2134f-5c98-49fe-b06b-72851762f6a0" />

## Conclusions

From the results, aircraft with electric engine types are recommended while those with reciprocating engine types should be avoided since they are involved in the highest fatalities and accident occurrences.
The company should purchase the Gates Learjet,24E which is the safest option for business purposes since it has the highest rates of uninjured users.
Helicopters are illustrated to be among the categories associated with the least total fatal injuries and is strongly recommended for business purposes.
The company should also steer clear of the A36 model as it is the least robust and suffers the highest aircraft damage and potentially the highest fatalities and accident rates.
A limitation of this analysis is that several features contain unknown values, hence it could mean that there is a level of bias to this analysis.
For future projects, the make and models could be grouped together to further narrow down on specific aircraft characteristics

## For More Information

Please review our full analysis in

For any additional questions, please contact **Shem Omondi, shemrodgers@gmail.com**

## Repository Structure

```
