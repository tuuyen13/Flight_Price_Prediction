# Flight_Price_Prediction
The goal of this study is to analyze a flight booking dataset obtained from the "Ease My Trip" website and conduct various statistical hypothesis tests to extract meaningful insights. The study will employ machine learning models to train the dataset and predict a continuous target variable. "Easemytrip" serves as an online platform for booking flight tickets, making it the primary choice for potential passengers when purchasing tickets. A comprehensive analysis of the dataset will facilitate the discovery of valuable insights that can greatly benefit passengers.

The dataset was sourced from Kaggle and includes information related to flights extracted from the Ease My Trip booking website. Ease My Trip is one of the leading travel companies in India and a trusted name in the Indian travel industry. The dataset contains information about economy and business class flights over a 50-day period, specifically from February 11th to March 31st, 2022. It covers data from 6 renowned airlines in India and comprises 300,261 rows with 11 data fields.

| Variables       | Description                                                         | 
|--------------------|---------------------------------------------------------------------|
| `Airline`           | Name of the airline company                                       |
| `Flight`              | Flight code                                                        | 
| `Source City`        | City from which the flight takes off                              | 
| `Departure Time`     | Departure time categorized into time bins                           | 
| `Stops`              | Number of stops between source and destination cities              | 
| `Arrival Time`       | Arrival time categorized into time bins                            |
| `Destination City`   | City where the flight will land                                   | 
| `Class`              | Seat class (Business or Economy)                                   |
| `Duration`           | Overall travel time between cities in hours                        |
| `Days Left`          | This is a derived characteristic that is calculated by subtracting the trip date from the booking date. |
| `Price`              | Target variable representing the ticket price                     | 




