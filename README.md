# API-INTEGRATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RUKSAR

*INTERN ID*: CT06DF2842

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

## 🌤️ Weather App

This Weather App is a responsive and  web application developed using **HTML**, **CSS**, and **JavaScript**, with data powered by the **OpenWeatherMap API**. The main goal of the project is to fetch and display **real-time weather information** for any city that the user enters. It was built as a practical exercise in API integration and DOM manipulation, allowing me to understand how to work with external data sources and display dynamic content on a web page.

The application consists of a simple interface where the user can type the name of a city and click the "Search" button. Once submitted, the app sends an HTTP request to the OpenWeatherMap API using the `fetch()` method in JavaScript. The API returns weather data in **JSON format**, including temperature (in Celsius), weather condition (like clear, cloudy, or rainy), humidity level, and wind speed. This information is then extracted from the JSON response and displayed on the page in a clean, readable format.

For styling, I used **CSS** to design a modern and user-friendly interface. The layout includes a centered input field and button, a result display box, and a visually pleasing background using gradients. The app is also **responsive**, meaning it adjusts to different screen sizes, making it usable on both desktop and mobile browsers.

To make the user experience smoother, I implemented **basic error handling**. If the user submits a blank input or enters a city that does not exist in the API’s database, the app shows a "City not found" message instead of crashing or returning raw errors. I also used `encodeURIComponent()` in JavaScript to handle special characters in city names (like spaces in “New York”), ensuring accurate API requests.

This project helped me strengthen my understanding of key web development concepts such as event handling, working with APIs, processing JSON data, and dynamically updating the DOM. It also introduced me to asynchronous JavaScript operations using `fetch()` and `.then()` chains for promise handling. The use of the **OpenWeatherMap API** gave me hands-on experience with real-world API services, including how to set up and manage API keys.

In the future, this project can be expanded by adding new features like weather icons, unit toggling between Celsius and Fahrenheit, location-based weather using the Geolocation API, and a 5-day weather forecast. These additions would not only enhance the app's functionality but also allow further learning in more advanced JavaScript topics.

Overall, this Weather App is a compact and effective project that showcases the integration of web technologies and third-party APIs. It is ideal for beginners who want to learn how to build interactive web applications using JavaScript and is a strong addition to any portfolio. It reflects my growing skills in frontend development and is a solid foundation for more complex JavaScript-based applications in the future.
