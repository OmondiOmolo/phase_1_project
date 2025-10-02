## Aviation Analysis Project
Author**: Shem Omondi

## Overview

The company wants to venture into the Aviation Business but has no prior knowledge of potential risks associated with aircrafts. The data of use which was collected and gathered by the NTSB was then cleaned and analyzed in order to gain insights on the different aircrafts' aviation statistics. Through pandas and its associated libraries, various methods of cleaning, analysis and visualizing the data were employed. Recommendations were made considering that the purpose of the flights was for Business.

## Business Problem

The challenge is that the company has no prior knowledge of potential risks associated with the aircrafts.
The aim is to determine which aircraft bears the least risk to the company as it starts this new business venture.

## Data

The data of use will be the cleaned version of the aviation dataset by the NTSB which was retrieved from Kaggle which is an open website containing various datasets.
The data consists of the following relevant features; the aircraft make and model, total fatal injuries, total uninjured people, the purpose of the flight, the accident location, the number of engines and engine type of involved aircrafts.
These features, while considering the purpose of the flight, can help to determine which aircrafts are safest to operate for the commercial and private enterprise venture.

## Methods

A number of methods were used to clean, analyze and visualize the data.
Pandas library was used to clean and analyze the data.
Some visualizations were also made with the aid of matplotlib.pyplot and seaborn.

## Results

### Total fatal injuries against Engine Type

<img width="712" height="424" alt="fatal injuries by engine type" src="https://github.com/user-attachments/assets/ccc53560-032f-4b5b-b119-12002e825e2a" />




### Number of uninjured people against aircraft model within make 
<img width="856" height="496" alt="safest aircraft by uninjured count" src="https://github.com/user-attachments/assets/cc1728fe-5c1c-44ac-aa03-1d3ee7a8b79e" />




### Aircraft Category against Total Fatal Injuries
<img width="712" height="424" alt="fatal injuries by aircraft category" src="https://github.com/user-attachments/assets/219f689d-35c4-494c-9318-d8fbf17639cc" />



## Conclusions

Aircraft with electric, LR and even Turbo fan engine types are recommended since they have the least total fatal injuries.
The company should purchase the Gates Learjet,24E, which is the safest option for business purposes since it has the highest rates of uninjured users.
Helicopters are illustrated to be among the categories associated with the least total fatal injuries and is strongly recommended for business purposes.
For future projects, the make and models could be grouped together to further narrow down on specific aircraft characteristics.

## For More Information

Please review our full analysis in https://github.com/OmondiOmolo/phase_1_project/blob/main/student.ipynb or https://github.com/OmondiOmolo/phase_1_project/blob/main/presentation/Aviation%20Data%20Analysis%20Presentation.pdf or
https://public.tableau.com/app/profile/shem.omondi/viz/projectvisualizationphase1/whatisthemainreasonbehindfatalaccidents

For any additional questions, please contact **Shem Omondi, shemrodgers@gmail.com**

## Repository Structure

``
  ├── images                                       <- contains the visualization we have used in this project
  ├── presentation                                 <- contains the presentation pdf
  ├── .gitignore                                   <- .gitignore contains files which are too large to commit
  ├── Aviation Data Analysis Presentation.pdf      <- PDF version of project presentation
  ├── README.md                                    <- The top-level README for reviewers of this project
  ├── Student.ipynb                                <- Narrative documentation of analysis in Jupyter notebook
