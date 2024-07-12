The Weather App is a professional web application designed to provide real-time weather information for any city worldwide. Users can easily search for a city and receive the latest temperature, humidity, wind speed, and an appropriate weather icon indicating current weather conditions. This app leverages the OpenWeatherMap API for accurate and up-to-date data.

Features
City Weather Search: Input any city name to get current weather data.
Real-time Data: Fetches and displays the latest temperature, humidity, and wind speed.
Dynamic Icons: Displays relevant weather icons based on current conditions (e.g., clear, cloudy, rainy).
Error Handling: Informs users when an invalid city name is entered.
Technologies Used
Frontend: HTML5, CSS3, JavaScript
API: OpenWeatherMap API

Setup and Usage
Prerequisites
Modern web browser (Chrome, Firefox, Edge, etc.)
Internet connection for API requests
Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/ravisankaradimula/Weather.git
cd weather-app
Open index.html
Open the index.html file in a web browser. This can be done by double-clicking the file or using a browser's "Open File" option.

Search for Weather Information

Enter a city name into the search input field.
Click the search button to retrieve and display the weather information.
API Key Configuration
The application requires an API key from OpenWeatherMap. The API key is embedded within the script section of index.html:

javascript
Copy code
const apikey = "2010a8be1671dfbcd990ab836c4b9fb1";
Note: For security and best practices, consider storing the API key securely and not exposing it directly in production environments.

Customization
Updating Weather Icons
To change the default weather icons, replace the existing image files in the images directory with new ones. Ensure the new files retain the same names as the originals for seamless integration.

Styling Adjustments
Modify the style.css file to customize the app's appearance. You can change colors, fonts, layout, and other styles to better suit your preferences or branding requirements.

Enhancing Error Handling
Currently, the app displays a basic error message for invalid city names. You can improve this by providing more detailed messages or additional styling. Update the .error section in both index.html and style.css to achieve this.

Contributing
We welcome contributions to enhance this project. Follow these steps to contribute:

Fork the Repository
Create a Feature Branch
bash
Copy code
git checkout -b feature-branch
Implement Your Changes
Commit Your Changes
bash
Copy code
git commit -m 'Description of feature or fix'
Push to Your Branch
bash
Copy code
git push origin feature-branch
Create a Pull Request
License
This project is licensed under the MIT License. See the LICENSE file for more details.
