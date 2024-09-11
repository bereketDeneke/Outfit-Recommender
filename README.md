# Weather-Based Outfit Recommendation System

This repository contains a Python-based application that fetches real-time weather data based on the user's current location and provides outfit recommendations accordingly. The recommendations are based on weather conditions such as temperature, wind speed, humidity, and precipitation.

## Purpose
The primary goal of this project is to help users decide what to wear based on the current weather conditions at their location. By using real-time weather data, this system ensures that the recommendations are relevant and timely. The use of emojis in the recommendations adds a fun and engaging visual element.

## Features
- Automatically detects the user's location using their IP address.
- Fetches the latest weather data using the [Tomorrow.io API](https://www.tomorrow.io/).
- Provides temperature, wind speed, humidity, and precipitation details.
- Offers clothing recommendations based on the weather data, displayed in markdown format with emojis.

## APIs Used

1. **IPInfo API** (https://ipinfo.io/)
   - Used to determine the user's location based on their IP address.
   - Provides information like city, country, latitude, and longitude, which are necessary for fetching the weather data.

2. **Tomorrow.io API** (https://www.tomorrow.io/)
   - Used to fetch detailed weather data, such as temperature, humidity, wind speed, and precipitation, for the user's location.
   - Chosen for its accurate and comprehensive real-time weather forecasting and easy integration with Python.

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/bereketDeneke/Outfit-Recommender.git
   ```

2. **Install dependencies:**
   Make sure you have Python 3 installed. You can install the necessary dependencies using:
   ```bash
   pip install requests
   ```

3. **Set up API keys:**
   - You'll need an API key from [Tomorrow.io](https://www.tomorrow.io/). Sign up, generate an API key, and replace the placeholder value in the code:
     ```python
     weather_api_key = "YOUR_TOMORROW_IO_API_KEY"
     ```
   - You don't need an API key for the IPInfo API, as it provides free access for IP-based location lookups.

4. **Run the application:**
   Execute the Python code in the notebook or script, and the system will:
   - Fetch your location via the IPInfo API.
   - Retrieve the weather details for your location using the Tomorrow.io API.
   - Provide a weather-based outfit recommendation displayed in markdown format.

5. **View the recommendations:**
   The weather details and outfit suggestions will be displayed in a markdown format using emojis for better visualization.

## Prerequisites

1. **Python 3.x** must be installed on your machine.
2. **API Key** from [Tomorrow.io](https://www.tomorrow.io/) for weather data.
3. Libraries:
   - `requests`: For making API requests.
   - `IPython.display.Markdown`: For rendering markdown within a notebook or Python environment.

### Example

## Current Weather Details in New York City, US:
- 🌡 **Temperature:** 21.0°C
- 🌬 **Wind Speed:** 2.0 km/h
- 💧 **Humidity:** 67.0%
- 💧 **Precipitation:** 0 mm

## Recommended Outfit:
☀ The average temperature is 21.0°C, with moderate wind. A t-shirt, shorts, and sunglasses will keep you comfortable throughout the day.

### Have a great day!
No matter what the weather is like, being prepared with the right clothing will help you enjoy it to the fullest.

## Authors
- 
```
