# DS5500
Real-Time Prediction of League of Legends Game Winning Rate

Real-time prediction of LoL game winning rates using the Random Forest model offers a novel approach to enhancing the gaming experience. By leveraging machine learning techniques, we can accurately predict game outcomes and provide players with valuable insights into the factors influencing victory.

## Data Collection

In dataCollection/ folder, main.py is collect data from Riot API.

Because of API limit, there will be multiple data csv file, then use mergeData.py to merge these csv to one file.

Data_process_train.ipynb is the file that clean and process data, then train multiple models and save model which has best performance.


## Installing website Dependencies

Download the source code into a folder of your choosing.

You'll need [Python version 3.9 or higher](https://www.python.org/downloads/), and the [latest version of Node.js](https://nodejs.org/en/) to continue.

To install the Python dependencies, navigate your terminal to the interface/backend/ folder and do:

```
$ pip install -r requirements.txt
```

To install the React dependencies, change directories to the interface/frontend/ folder, and do:

```
$ npm install
```

## Running the Project

After installing both the Python and React dependencies, I recommend having two terminal instances: one for the front-end and back-end of the application.

Navigate your back-end terminal to the interface/frontend/ folder and do:

```
$ flask run
```

or execute the app.py script in your code editor to run the back-end API.

Navigate your front-end terminal to the interface/frontend/ folder, and do:

```
$ npm run start
```

to run the front-end API. This should automatically launch the development build in your browser.


