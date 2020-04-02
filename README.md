# Disaster Response Pipeline Project

### Instructions:
1. Run the following commands in the project's root directory to set up the database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run the web app.
    `python run.py`
    
3. Go to http://0.0.0.0:3001/

### Files/Folders :
The Project contains the following folders

app: files related to the Web App

data: contains csv files , database file and data processing script

models: contains the trained classifier and the respective script

### Web App

![Web App Screenshots](https://imgur.com/a/phZ1NuD)
