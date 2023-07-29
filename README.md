# Weather-App
The Weather App is a simple web application that allows users to check the current weather conditions for a specific location. It is built using HTML, CSS, and JavaScript and utilizes a weather API to fetch real-time weather data.

Features :

1.Check the current weather conditions for a given location.

2.Display the temperature, weather description, and other relevant weather data.

3.Support for various cities and locations around the world.



Usage: 


a.Upon loading the Weather App, you will see an input field where you can enter the name of a city or location.

b.Press the "Search" button or hit the "Enter" key to fetch and display the current weather data for the entered location.

c.The weather information will include the temperature, weather condition, humidity, wind speed, and any additional relevant details.


Dependencies :

The Weather App does not rely on any external libraries or frameworks. It uses the following technologies:

i. HTML: The structure and layout of the web application.

ii. CSS: Styling and layout of the user interface.

iii. JavaScript: For fetching data from the weather API and updating the UI dynamically.


API :

The Weather App uses the OpenWeatherMap API to fetch weather data. You will need to obtain an API key from OpenWeatherMap and add it to the script.js file in the designated section for the API key.


 const api_key = "325497960746f804d102dba55a9f080e";
 
const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${api_key}`;



Weather App Screenshot :

![output](https://github.com/Ranasakshi12345/Weather-App/assets/123829259/3c32f3e4-5e39-4dc4-aa16-b1580381fc68)


