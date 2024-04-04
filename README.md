# Weather_COD5436

Internship : CODTECH IT SOLUTIONS

Name : Aluganti Supriya
ID : COD5436

Task-2 : Weather Forecast web Application

Code Explaination : 

### HTML:
- The HTML structure defines the layout of the application, including input elements for searching locations, weather information display sections, and an image for showing weather conditions.

### CSS:
- The CSS file styles the HTML elements, defining their appearance, layout, and animations.
- It sets styles for the container, search box, weather information display, and error message display.

### JavaScript:
1. **DOM Selection:**
   - It selects various elements from the DOM using `document.querySelector`.

2. **Asynchronous Function `checkWeather`:**
   - This function fetches weather data from the OpenWeatherMap API based on the city entered by the user.
   - It handles the response and updates the UI with the weather information.
   - If the city is not found (`cod === '404'`), it displays a "Location not found" message.

3. **Event Listener:**
   - `click` event on the search button (`searchBtn`): Calls the `checkWeather` function with the value entered in the input box (`inputBox.value`).
Conclusion :
- When the user enters a city name and clicks the search button, the JavaScript code fetches weather data from the OpenWeatherMap API for that city.
- It then displays the temperature, weather description, humidity, wind speed, and an image representing the weather condition.
- If the city is not found or there's an error in fetching the data, it displays a "Location not found" message.
- The CSS styles ensure that the UI is visually appealing and responsive.

The application provides a simple way for users to check the weather conditions of a specific location.
