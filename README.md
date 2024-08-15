 Weather Information App

 Overview
The Weather Information App is a Java-based application that provides real-time weather updates for a specified location. The app features a graphical user interface (GUI) developed using Java Swing, allowing users to search for weather information, view detailed weather conditions, and track their search history. The app integrates with the OpenWeatherMap API to fetch weather data and display relevant information, including temperature, humidity, wind speed, and weather conditions.

 Features
- API Integration: Retrieves real-time weather data from the OpenWeatherMap API.
- User-Friendly GUI: Allows users to input a location and displays weather details using a clear and intuitive interface.
- Unit Conversion: Supports conversion between Celsius and Fahrenheit for temperature and between km/h and mph for wind speed.
- Weather Icons: Displays visual icons representing the current weather conditions.
- Forecast Display: Shows a short-term weather forecast for the selected location.
- Search History: Tracks and displays the history of recent weather searches with timestamps.
- Dynamic Backgrounds: Changes the app background based on the current weather conditions.

 Installation and Setup
 Prerequisites
- Java Development Kit (JDK) 8 or later.
- An internet connection to fetch weather data from the OpenWeatherMap API.

 Steps to Run the Application
1. Clone or Download the Repository:
   - Clone the repository using `git clone` or download the source code as a ZIP file and extract it.

2. Open the Project in an IDE:
   - Open the project in your preferred Java Integrated Development Environment (IDE), such as IntelliJ IDEA, Eclipse, or NetBeans.

3. Add API Key:
   - Replace the placeholder API key in the `WeatherAPI.java` file with your own OpenWeatherMap API key.

4. Compile and Run:
   - Compile the project and run the `Main.java` file to start the application.

5. Using the Application:
   - Enter the name of a city or coordinates in the input field and click "Search" to fetch weather details.
   - The application will display the current temperature, humidity, wind speed, and weather conditions, along with an appropriate icon.
   - You can switch between Celsius and Fahrenheit using the dropdown menu.
   - The app will show a short-term weather forecast and keep a record of your recent searches.

 API Integration
The application uses the OpenWeatherMap API to retrieve weather data. The `WeatherAPI.java` class handles the API calls, fetching data as a JSON object, which is then parsed to extract relevant information such as temperature, humidity, wind speed, and weather conditions.

 GUI Design
The GUI is designed using Java Swing, structured within a main panel that includes input fields, labels for displaying weather data, a forecast area, and a search history list. The layout is managed using a combination of `BoxLayout` and `JPanel` components to ensure a clean and organized interface.

 Unit Conversion
The `UnitConverter.java` class provides methods to convert temperature between Celsius and Fahrenheit and wind speed between km/h and mph. The app automatically updates the displayed units based on user selection.

 Error Handling
The app includes basic error handling for scenarios such as invalid location input or failed API requests. If an error occurs, a message is displayed to the user.

 History Tracking
The `WeatherHistory.java` class stores weather data for each location searched, allowing users to view their search history along with timestamps.

 Dynamic Backgrounds
The background color of the app changes dynamically based on the current weather conditions (e.g., clear sky, clouds, rain).

 License
This project is licensed under the MIT License. See the LICENSE file for more details.
