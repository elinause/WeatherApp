🌤️ Weather App

A desktop weather application built with Python and PyQt5 that retrieves real-time weather information using the OpenWeatherMap API.

📌 Project Overview

The Weather App allows users to enter a city and retrieve current weather information, including temperature, weather conditions, and a corresponding weather emoji.

This project was created to practice Python programming, PyQt5 GUI development, API integration, JSON data handling, and Git/GitHub version control.

✨ Features

🌍 Search weather by city

🌡️ Display temperature in Celsius

☁️ Display current weather conditions

😊 Display weather emojis based on weather conditions

🔄 Retrieve real-time weather data

⚠️ Handle invalid city names and API errors

🖥️ User-friendly desktop interface

🛠️ Technologies Used

Python

PyQt5

Requests

OpenWeatherMap API

Git & GitHub

📂 Project Structure

WeatherApp/

│

├── main.py

├── README.md

├── requirements.txt

└── .gitignore

⚙️ Installation

1. Clone the repository
git clone https://github.com/elinause/WeatherApp.git
2. Open the project

   Open the project folder in PyCharm or another Python IDE.

3. Create a virtual environment

python -m venv .venv

Activate it on Windows:

.venv\Scripts\activate
4. Install the required packages

pip install -r requirements.txt

🔑 OpenWeatherMap API

This application uses the OpenWeatherMap API to retrieve weather information.

You will need your own API key.

Create an account on OpenWeatherMap and obtain an API key.

Important: Do not upload your private API key to GitHub.

For better security, store your API key in an environment variable instead of writing it directly in your Python source code.

▶️ Running the Application

After installing the required packages and configuring your API key, run:

python main.py

The Weather App window will open. Enter a city name and click the weather button to retrieve the current weather information.

📸 Screenshot

Add a screenshot of your application here:

![Weather App Screenshot](screenshot.png)

After taking a screenshot, save it in your project folder with the name:

screenshot.png

Then commit and push it to GitHub.

🎯 Learning Objectives

This project helped me practice:

Python classes and functions
Object-oriented programming
PyQt5 GUI development
Working with APIs
Sending HTTP requests
Processing JSON responses
Exception and error handling
Git and GitHub
Project documentation
🚀 Future Improvements

Possible future improvements include:

Add a 5-day weather forecast
Add weather icons
Add humidity and wind speed
Add sunrise and sunset information
Improve the user interface
Add automatic location detection
Store recently searched cities
Improve API-key security using environment variables
👨‍💻 Author

Okechukwu Igbelina

GitHub: @elinause

📄 License

This project is available for educational and personal use.