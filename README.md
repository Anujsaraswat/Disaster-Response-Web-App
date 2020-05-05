# Disaster Response Pipeline Project

## Instructions
1. Run the following commands in the project's root directory to set up the database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run the web app.
    `python run.py`
    
3. Go to http://0.0.0.0:3001/

## Directories
The Project contains the following folders

- `App`: files related to the Web App

- `Data`: contains csv files , database file and data processing script

- `Models`: contains the trained classifier and the training script

## Requirements
- sklearn
- nltk
- pandas
- numpy
- joblib
- re
- Flask

## Web App
1. Main Page

![Web App Screenshot](https://user-images.githubusercontent.com/57795947/78289639-180bba80-7540-11ea-9a83-efaa80364ccb.PNG)

2. Classifying text

![Web App in Action](https://user-images.githubusercontent.com/57795947/78289933-881a4080-7540-11ea-855e-138570a0064f.PNG)
