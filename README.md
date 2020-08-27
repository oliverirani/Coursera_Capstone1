# Coursera_Capstone1
This is the repository for the IBM data science professional certificate final project

### Clearly define a problem or an idea of your choice. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.
This project is about analyzing the severity of collisions in Seattle area in the USA. As part of this capstone project we will be developing a predictions model to predict the collisions severity in Seattle area in the United States of America. The main problem: What is the severity magnitude for a collision to occur in Seattle?

Audience consists of people who lives in Seattle or travel through it and goal is to provide them information about current situation on a roads and possible dangers.

Audience should be interested in this problem because knowing the relationships between conditions and likelihood of collision can save their money and life.


### Describe the data that you will be using to solve the problem or execute your idea. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using.
This dataset contains about 6.5 mln car collisions records. The data include all types of collisions. Collisions will display at the intersection or mid-block of a segment. The data are collected from a timeframe of 2004 to Present. The data is updated on a weekly basis and is provided by SPD and recorded by Traffic Records.

Data set has 194673 rows and 38 columns. After checking the data there is a need to clean them and select main features used in the further analysis. 

The analysis focuses on the following columns because they are relevant to the analysis:
•	COLLISIONTYPE: A keyword describing the collision, eg 'head-on', 'angled', 'cycles', etc.
•	PERSONCOUNT: Total number of people involved in the collision.
•	PEDCOUNT: The number of pedestrians involved in the collision.
•	PEDCYLCOUNT: The number of bicycles involved.
•	VEHCOUNT: The number of vehicles involved in the collision.
•	INCDATE/INCDTTM: Date and time recordings for the incident records.
•	INATTENTIONIND: If collision was due to inattention.
•	UNDERINFL: If driver was under influence of drugs/alchohol.
•	WEATHER: Weather at the time of incident.
•	ROADCOND: Condition of road at the time of incident.
•	LIGHTCOND: Light conditions at the time of incident.
•	SPEEDING: If speeding was a factor in the collision.

By utilising independent values in machine learning models I determined the SEVERITYCODE.
