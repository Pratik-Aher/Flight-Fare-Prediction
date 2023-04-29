                                      **ONGOING**
# Flight Fare Prediction


* Created a tool that estimates Flight Prices to help users look for best prices when booking flight tickets.
* Engineered features from the Departure Time, Date of Journey, to quantify the data and make it more understandable.

## Project Members:
- Aakash Dabhade
- Pratik Aher
- Prathamesh Koli






## Additional Information 


* Problem Statement:
The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planning the trip will surely help many people save money and time.

The main goal is to predict the fares of the flights based on different factors available in the provided dataset.


The various independent features in the dataset were:

* Size of test set: 2671 records
* FEATURES: Airline: The name of the airline.
* Date_of_Journey: The date of the journey
* Source: The source from which the service begins.
* Destination: The destination where the service ends.
* Route: The route taken by the flight to reach the destination.
* Dep_Time: The time when the journey starts from the source.
* Arrival_Time: Time of arrival at the destination.
* Duration: Total duration of the flight.
* Total_Stops: Total stops between the source and destination.
* Additional_Info: Additional information about the flight
* Price: The price of the ticket


Flight Ticket Prices Dataset = [ Dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh) 
## Flow of Project

* Application Architecture:


  ![proj2_flowchart](https://user-images.githubusercontent.com/54064843/136836342-6b4bb5a5-7b97-40af-aa34-f646b1800a37.jpg)


* Code :
   * Data Ingestion
   * Data Preprocessing
   * Model Selection
   * Predection
   * Logging Framework
   * Deployment


## Deployment

The code is written in Python 3.6.10. If you don't have Python installed, you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```bash
  pip install -r requirements.txt
```
**Deployment on Heruko**

Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually to deploy this project.

__    ss of heruko and link

#


The next step would be to follow the instruction given in the Heroku Documentation 
[Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python)
to deploy a web app.





## Run Locally

1.Ensure that you are in the project home directory. Create the machine learning model by running below command -

```bash
  python model.py
```
This would create a serialized version of our model into a file model.pkl

2.Run app.py using below command to start Flask API

```bash
  python app.py
```

By default, flask will run on port 5000.

3.Navigate to URL http://127.0.0.1:8000/ (This local server will be assigned after you run the unicorn command)



## Cleaning the Data

We needed to clean it up so that it was usable for our model.We made the following changes and created the following variables:
* Made Columns for Day and Month out of Date of Journey
* Calculated the total flight duration
* Removed the null values
* Removed the outliers



## Model Building

First, We transformed the categorical var
