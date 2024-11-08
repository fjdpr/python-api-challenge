# WeatherPy and VacationPy

## Summary
This project includes two scripts: `WeatherPy` and `VacationPy`.

`WeatherPy` analyzes the relationship between various weather variables and latitude, while `VacationPy` searches for ideal vacation destinations based on specific weather conditions and finds nearby hotels using the Geoapify API.

## Objectives
### WeatherPy
- Generate a list of random geographic coordinates and obtain weather data for each city.
- Create scatter plots to visualize the relationships between weather variables and latitude.
- Compute linear regression for each relationship between the variables and latitude.

### VacationPy
- Create a map that shows points for each city based on humidity.
- Filter cities according to ideal weather conditions.
- Use the Geoapify API to find hotels near the selected locations.

## Data Description
### WeatherPy
The dataset includes:
- Cities
- Geographic coordinates (latitude and longitude)
- Maximum temperature
- Humidity
- Cloudiness
- Wind speed
- Country
- Date

### VacationPy
The dataset includes:
- Cities
- Geographic coordinates (latitude and longitude)
- Maximum temperature
- Humidity
- Country
- Hotel names

## Script Included
- `WeatherPy`: Generates plots and analysis of the relationship between weather variables and latitude.
- `VacationPy`: Analyzes and visualizes weather data to find ideal vacation destinations and nearby hotels.

## Requirements
- Python 3.10
- pandas module
- matplotlib module
- numpy module
- requests module
- scipy module
- citipy module
- hvplot module

## Instructions
### WeatherPy
1. Ensure that `api_keys.py` contains your OpenWeatherMap API key.
2. Run the WeatherPy script to generate the plots and analysis.

### VacationPy
1. Ensure that `api_keys.py` contains your Geoapify API key.
2. Run the VacationPy script to generate the maps and analysis.

## Contributions
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
