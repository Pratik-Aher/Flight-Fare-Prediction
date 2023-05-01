                                      **ONGOING**
# Flight Fare Prediction


* Created a tool that estimates Flight Prices to help users look for best prices when booking flight tickets.
* Engineered features from the Departure Time, Date of Journey, to quantify the data and make it more understandable.

## Project Members:
- Aakash Dabhade
- Pratik Aher
- Prathamesh Koli
<br><br>

##  Screenshots

<img src = '/assets/1.png'>
<img src = '/assets/2.png'>



<br><br>
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

<br><br>
## Deployment

The code is written in Python 3.6.10. If you don't have Python installed, you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```bash
  pip install -r requirements.txt
```

<br><br>
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

<br><br>

## Cleaning the Data

We needed to clean it up so that it was usable for our model.We made the following changes and created the following variables:
* Made Columns for Day and Month out of Date of Journey
* Calculated the total flight duration
* Removed the null values
* Removed the outliers

<br><br>

## Visualization

Graph of Features for better visualization
<br>
<img src = '/assets/features.png'>

<br><br>
## Model Building

**Fitting Model Using Random Forest**<br>

Split data into train and test so as to predict w.r.t. 'X_test'.<br>

If needed do scaling of data a) scaling is not done in Random Forest<br>

Import the model(which suits the data most or gives better results) Fit training data into it<br>

Predict w.r.t. 'X_test' (compare with 'Y_test')<br>

<br><br>

## Regression models score
MAE: 1176.8211626134876 <br>
MSE: 4372706.25598775 <br>
RMSE: 2091.1016847556098 <br>

<br><br>

## Contact

<div align="center">
<h3> Connect with me<a href="https://gifyu.com/image/Zy2f"><img src="https://github.com/milaan9/milaan9/blob/main/Handshake.gif" width="50px"></a>
</h3> 
<p align="center">
<a href="mailto:aherpratik00@gmail.com" target="_blank"><img alt="Gmail" width="25px" src="https://cdn-icons-png.flaticon.com/512/5968/5968534.png"></a>&nbsp&nbsp&nbsp
<a href="https://www.linkedin.com/in/pratik-aher01/" target="_blank"><img alt="LinkedIn" width="25px" src="https://cdn-icons-png.flaticon.com/512/3536/3536505.png"></a> &nbsp&nbsp&nbsp
    
   
    
</p> 
