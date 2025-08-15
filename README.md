Name: Vaishnavi Deoaro Sonkusare
Company: CODTECH IT SOLUTIONS
ID: CT08DG1674
Domain: Python Programming
Duration: June to August 2025
Mentor: NEELA SANTOSH KUMAR


##Overview of Project

 Project Title: Weather Data Visualization Dashboard

 <img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/a7537e90-2eaf-413c-87db-612144fa6e43" />
 <img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/0c895900-1892-4ede-aba9-d255cd976c6f" />
 <img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/17e654c4-a680-46ce-8a39-1ffe81b3f8e0" />


 Objective:
The project fetches weather forecast data from the OpenWeatherMap API for a given city, processes it, and visualizes key weather parameters (temperature, humidity, and weather conditions) in an easy-to-understand graphical format.

Workflow Overview:

Fetch Data
Uses the OpenWeatherMap 5-day/3-hour forecast API.
Retrieves temperature, humidity, and weather descriptions at 3-hour intervals for the next 5 days.
The fetch_weather_data() function handles API requests and checks for errors.
Parse Data
Extracts date/time, temperature, humidity, and weather condition descriptions from the API response.
The parse_weather_data() function organizes this data into lists for plotting.
Visualize Data
Temperature Trend: Line chart showing temperature changes over time.
Humidity Trend: Line chart showing humidity variations.
Weather Condition Frequency: Bar chart (via sns.countplot) showing the frequency of different weather descriptions (e.g., cloudy, sunny, rain).
The create_dashboard() function creates these plots with matplotlib and seaborn.
User Interaction
The user inputs a city name.
Data is fetched and visualized dynamically for that city.

Technologies Used:

Python
Requests (API calls)
Matplotlib & Seaborn (data visualization)
Datetime (time formatting and conversion)

Key Features:

Works for any city supported by the API.
Visualizes both numerical trends (temperature/humidity) and categorical data (weather descriptions).
Uses clear and well-labeled charts for better readability.
