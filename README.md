# codetech_task_2.1

Name:Parth Deorukhkar

Company:CODETECH IT SOLLUTION

ID:CT08EIV

Domain:Python

Duration:Dec17 to Jan 17

Mentor:Neela Santosh Kumar



Weather Data Analysis and Visualization
This Python script fetches weather data for a given city using the OpenWeatherMap API, processes the data, and visualizes temperature, humidity, and weather conditions using line and count plots.

Features
Fetches 5-day weather forecast data from the OpenWeatherMap API.
Extracts and parses key weather details such as:
Date and Time
Temperature (in °C)
Humidity (in %)
Weather conditions (e.g., Clear, Rainy, Cloudy).
Creates the following visualizations using Matplotlib and Seaborn:
Temperature forecast over time.
Humidity forecast over time.
Frequency of weather conditions.
Requirements
Install the required Python libraries:
requests: For API calls.
matplotlib: For creating plots.
seaborn: For enhanced visualizations.
pandas: For data manipulation.
Install these libraries using:

bash
Copy code
pip install requests matplotlib seaborn pandas
Setup and Usage
Get an OpenWeatherMap API Key:

Sign up at OpenWeatherMap.
Create an API key for accessing the weather data.
Configure the script:

Replace API_KEY in the script with your OpenWeatherMap API key.
Update CITY with the desired city name (e.g., London, New York, etc.).
Run the script:

bash
Copy code
python script_name.py
Replace script_name.py with the name of your script.

Debugging Setup (Optional): If the script fails to fetch data, use the debugging section provided to check the API response status and errors.

Example Output
1. Data Sample
After fetching and parsing data, the script produces a DataFrame like this:

yaml
Copy code
             datetime  temperature  humidity   weather
0  2025-01-14 12:00:00         8.5        72     Clear
1  2025-01-14 15:00:00         9.0        70     Cloudy
2  2025-01-14 18:00:00         6.5        80     Rain
3  2025-01-14 21:00:00         4.2        85     Rain
4  2025-01-15 00:00:00         3.8        88     Clear
2. Visualizations
a. Temperature Forecast
Line plot showing temperature changes over time.
b. Humidity Forecast
Line plot showing humidity changes over time.
c. Weather Condition Frequency
Bar plot displaying the frequency of different weather conditions.
Error Handling
Invalid City Name or API Key:

The script prints an error message if the API request fails.
Ensure the city name is spelled correctly, and the API key is valid.
Empty or Incomplete Data:

If the API does not return sufficient data, the script will handle the case gracefully with appropriate error messages.
Future Enhancements
Add more visualizations (e.g., wind speed, pressure).
Support for saving plots as images or embedding them in reports.
Extend to allow comparison of weather data across multiple cities.


![WhatsApp Image 2025-01-13 at 19 21 09_664140e9](https://github.com/user-attachments/assets/d8192ba1-2cf8-4905-b5cb-6115c0b8de8d)

![WhatsApp Image 2025-01-13 at 19 21 43_f58fb60e](https://github.com/user-attachments/assets/da591098-3886-4f27-8a1c-39bf248dc81d)

![WhatsApp Image 2025-01-13 at 19 22 15_7b15b6b4](https://github.com/user-attachments/assets/4d83f0a3-0253-4968-b434-36f49077b083)

![WhatsApp Image 2025-01-13 at 19 23 05_59a3a360](https://github.com/user-attachments/assets/67f05610-948c-4b5c-b92e-80f8fc4dc3ab)

![WhatsApp Image 2025-01-13 at 19 23 41_748323d6](https://github.com/user-attachments/assets/be016f35-342f-4a86-b252-51a292ec2ad4)
