# Explaination of the project

This project implements a simple weather API using Flask, allowing users to retrieve current weather information for multiple locations. The weather data is fetched from the OpenWeatherMap API.

# Prerequisites

Python
Flask
Requests library
Brief Procedure

# Install the required libraries.
Get your OpenWeatherMap API key.
Run the application.
Open Postman and create a new request to http://127.0.0.1:5000/weather with the GET method.
Add a query param location with the value being the city and state (eg: Bengaluru, KA).
Send the request and check the output.
NOTE: You can check the accuracy of the retrieved weather data by OpenWeatherMap.
Detailed explanation

# Run the python script in VScode
In the terminal you can see the base url http://127.0.0.1:5000. When you click on this url, you will see 404 error.
Now go to your Postman workspace, set the request type to GET.
Enter the URL for your Flask API endpoint i.e, http://127.0.0.1:5000/weather?.
Click on the "Params" tab. In the "Key" column, enter location. In the "Value" column, enter the city and state for which you want to retrieve the weather information.
Click the send button to make the request.
Now go back to the base url, inorder to fetch the weather data, you have to append the base url with the api endpoint i.e, http://127.0.0.1:5000/weather?city=city_name (eg: http://127.0.0.1:5000/weather?city=Bengaluru).
Now you can see the json file.

# screenshots
<img width="1440" alt="Screenshot 2023-11-28 at 9 26 50 AM" src="https://github.com/Seeree123/weather-api/assets/150243785/6a6f1527-d9fd-4160-a7a1-3d8b1cc1d858">
<img width="1440" alt="Screenshot 2023-11-28 at 9 26 21 AM" src="https://github.com/Seeree123/weather-api/assets/150243785/5e930a4a-be82-4416-ac84-89571c7f77d5">
<img width="1440" alt="Screenshot 2023-11-28 at 9 27 43 AM" src="https://github.com/Seeree123/weather-api/assets/150243785/95e265ea-83ba-4dd2-910d-97d48547bad7">




