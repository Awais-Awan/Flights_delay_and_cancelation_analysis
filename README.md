# Flight Delay and Cancellation Analysis (2022)

This project analyzes flight delays, cancellations, and their possible relation to weather conditions such as wind speeds for the year 2022. The analysis aims to identify the routes and airlines with the highest departure delays and cancellations and examine the impact of wind speeds on departure delays at various airports.

## Project Overview

- **Route Analysis**: Identifies the top flight routes with the highest mean departure delays and cancellations.
- **Airline Analysis**: Highlights the airlines with the highest mean departure delays and total cancellations.
- **Weather Analysis**: Investigates the impact of wind speeds (≥ 10 mph) on departure delays at different airports.

### Dataset
The project uses two CSV files:
- `flights2022.csv`: Contains data on flights, including delays and cancellations.
- `flights_weather2022.csv`: Includes weather-related data (specifically wind gust speeds) for the airports.

### Key Metrics Analyzed:
- **Mean Departure Delay**: The average delay in minutes for departures.
- **Total Cancellations**: The number of canceled flights, measured by missing departure times.
- **Wind Impact**: The relationship between wind speeds (10+ mph) and departure delays.

## Features

1. **Route Analysis**: 
   - Calculates the mean departure delay and total cancellations for each unique flight route.
   - Identifies routes with the highest delays and cancellations.
   - Visualizes the top 9 routes with the highest number of cancellations.

2. **Airline Analysis**:
   - Computes the mean departure delay and total cancellations for each airline.
   - Displays the airlines with the highest mean departure delays and the most cancellations.
   - Visualizes the top 9 airlines with the highest departure delays.

3. **Weather Analysis**:
   - Investigates the impact of wind gusts (≥ 10 mph) on departure delays at different airports.
   - Groups flights based on wind speed and calculates mean departure delay for each wind group.

## Visualizations

The project includes the following visualizations:
- **Bar Graph**: Routes with the highest number of cancellations.
- **Bar Graph**: Airlines with the highest mean departure delays.
- **Table**: Impact of wind speeds (≥ 10 mph) on departure delays by airport.

