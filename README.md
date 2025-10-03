## Aviation Analysis Project
Author**: Shem Omondi

## Overview

The company wants to venture into the Aviation Business but has no prior knowledge of potential risks associated with aircrafts. This project utilizes data from the NTSB to gain insights and identify the safest aircraft options for business use. Using Python libraries such as pandas, matplotlib, and seaborn, the dataset was cleaned, explored, and visualized to support data-driven recommendations.

## Business Problem

The challenge is that the company has no prior knowledge of potential risks associated with the aircrafts.
The aim is to determine which aircraft bears the least risk and highest safety standards specifically to business flights as it plans to start this new business venture.

## Data

The data, collected by the NTSB, was retrieved from Kaggle which is an open website containing various datasets.
The data consists of the following relevant features:

1.The aircraft make and model. 

2.Total fatal injuries.

3.Total uninjured people.

4.The purpose of the flight.

5.The accident location.

6.The number of engines.

7.Engine types.

These features, while considering the purpose of the flight, can help to determine which aircrafts are safest to operate for the commercial and private enterprise venture.

## Methods

The analysis involved:
- Data Cleaning: Using pandas to handle missing values and standardize entries
- Exploratory Analysis: Identifying trends and patterns in accident data
- Visualization: Leveraging matplotlib and seaborn to present insights graphically


## Results

### Total fatal injuries against Engine Type

<img width="712" height="424" alt="fatal injuries by engine type" src="https://github.com/user-attachments/assets/ccc53560-032f-4b5b-b119-12002e825e2a" />




### Number of uninjured people against aircraft model within make 
<img width="856" height="496" alt="safest aircraft by uninjured count" src="https://github.com/user-attachments/assets/cc1728fe-5c1c-44ac-aa03-1d3ee7a8b79e" />




### Aircraft Category against Total Fatal Injuries
<img width="712" height="424" alt="fatal injuries by aircraft category" src="https://github.com/user-attachments/assets/219f689d-35c4-494c-9318-d8fbf17639cc" />



## Conclusions

1.Aircraft with electric, LR and even Turbo fan engine types are recommended since they have the least total fatal injuries.

2.The company should purchase the Gates Learjet,24E, which is the safest option for business purposes since it has the highest rates of uninjured users.

3.Helicopters are recommended for business flights among the different aircraft categories because they have the least total fatalities after data analysis.

4.For future projects, the make and models could be grouped together to further narrow down on specific aircraft characteristics.

## For More Information

Please review our full analysis in https://github.com/OmondiOmolo/phase_1_project/blob/main/student.ipynb 

https://github.com/OmondiOmolo/phase_1_project/blob/main/presentation/Aviation%20Data%20Analysis%20Presentation.pdf 

https://public.tableau.com/app/profile/shem.omondi/viz/projectvisualizationphase1/whicharethesafestandmostreliableaircraftsforbusinessflights?publish=yes

For any additional questions, please contact:

Email: **shemrodgers@gmail.com**

## Repository Structure


├── images                                   <- a folder that contains the visualization in this project.

├── presentation                             <- a folder that contains the presentation pdf.

├── .gitignore                               <- .gitignore contains files which are too large to commit.

├── Aviation Data Analysis Presentation.pdf  <- PDF version of project presentation.

├── README.md                                <- The top-level README for reviewers of this project.

├── Student.ipynb                            <- Narrative documentation of analysis in Jupyter notebook.

