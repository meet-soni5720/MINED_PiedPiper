# Team Pied Piper

## Remote Medicare - Hack 2021

Description:
The platform enables the doctor to remotely examine the patient based on the data of the patient’s vitals. Patients have their own personal health assistant. Our chatbot also helps doctor to predict disease based on symptoms.
It also predicts if a person is infected by covid using audio of coughing.

How to run the project:

To run the nodejs app (main dashboard website):
  `cd Hack_2021`
  `yarn install`
  `yarn build`
  `yarn start`
The app will run on http://localhost:8000/

To run the disease prediction flask app and covid prediction python program:
  `cd flask_app_covid_from_cough`
  `python app.py`
Then go to the url given in the command line
For disease prediction go to url/predict
For covid prediction go to url/audio
