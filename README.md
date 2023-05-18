# Scenario - SERC Fd in Computing

SERC School of Computing (and Engineering) would like to better understand the demographics of students who apply for and study the Foundation Degree in Computing. Additionally, they are also interested in creating a ML model that can predict the likelihood of a student passing certain modules, based on their pre-enrolment assessment score and current module grades.

## Tasks

1. Create a data warehouse to store the data provided in the files below, ready to be used for analysis. 
   - You should create a star schema, with a fact table and dimension tables.
   - You should create a data pipeline to load the data into the data warehouse.
   - The pipeline should:
      - automatically improve the quality of the data
      - remove personal data from the data set before loading it into the data warehouse
      - automatically update the data warehouse when new data is available

2. Create an ML model to predict student outcomes.
    - You should create a ML model that can predict the likelihood of a student passing certain modules, based on their pre-enrolment assessment score and current module grades.
    - You should use a suitable ML algorithm to create your model.
    - It is suggested to use a Python notebook to create, test and evaluate your model.
    - Investigate how to deploy your model to a production environment.
