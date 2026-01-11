# Weather-Prediction-Application-main
🌦 Weather Prediction Application

A simple Weather Prediction web app that displays current weather information and forecasts using public weather APIs and JavaScript.

 Overview

This project uses HTML, CSS, and JavaScript to build a frontend user interface that fetches live weather data from a weather API and shows it in an easy-to-read format. It may also include basic prediction features for short-term weather trends.

 Features

✔ Fetch and display current weather for a city
✔ Shows temperature, humidity, wind speed, and conditions
✔ Responsive layout for desktop & mobile devices
✔ Easy-to-use search field for entering city names
✔ (Optional — add if implemented) Short-term weather prediction using historical data

 How It Works

User enters a city name in the search bar.

JavaScript sends a request to a weather data provider API (e.g., OpenWeatherMap).

The app parses the API response and updates the UI with the weather details.

(Optional) It applies simple prediction or trend logic based on past API responses.

Tech Stack

Frontend: HTML, CSS, JavaScript

API: OpenWeatherMap (or similar weather data API)

Styles: Custom CSS (Bootstrap if added)

Weather-Prediction-Application-main/
│
├── index.html        
├── style.css           
├── script.js           
│
├── images/             
├── README.md           
│
└── other-resources/    


 Setup

Clone the repository

git clone https://github.com/Chaitanya2710/Weather-Prediction-Application-main.git


Get API Key

Sign up for OpenWeatherMap API (https://openweathermap.org/api
)

Copy your API key.

Update the API key

In script.js (or whichever JS file handles the API request):

const apiKey = "YOUR_API_KEY_HERE";


Open the app in browser

Simply open index.html in a web browser.

 Usage

Enter a city name into the search field and press Enter or click the search button. The weather information for that city will be displayed.


Future Enhancements

Add hourly or 7-day weather forecast

Save search history

Add icons for different weather conditions

Improve prediction with machine learning
 License

This project is MIT Licensed (or change to whatever license you prefer).
