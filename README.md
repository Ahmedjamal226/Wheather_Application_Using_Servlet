☁️ Weather Web Application
A dynamic, real-time weather forecasting application built using Java J2EE technologies. This project fetches live data from the OpenWeatherMap API to provide users with accurate weather details for any city worldwide.
🚀 Features:
Live Weather Updates: Displays current temperature in Celsius, humidity levels, and wind speed.
City-Based Search: Users can enter any city name to get instant weather data.
Dynamic Weather Icons: The UI automatically updates weather icons (Sun, Clouds, Rain, Mist, Snow, Haze) based on the actual weather condition returned by the API.
Clean UI/UX: Features a modern design with a linear gradient background and responsive elements.
🛠️ Technologies Used:
Backend: Java Servlets (J2EE).
Frontend: JSP (JavaServer Pages), HTML5, CSS3.
JSON Parsing: Google Gson library.
API: OpenWeatherMap API.
Icons & Fonts: Font Awesome & Google Fonts (Ubuntu).
📸 Preview:
![WhatsApp Image 2026-02-27 at 10 34 16 PM](https://github.com/user-attachments/assets/31afea64-2b26-4845-8210-035c6ac22167)
📂 Project Structure:
MyServlet.java: Handles the API connection, processes JSON data, and manages temperature conversion (Kelvin to Celsius).
index.html: The welcome landing page with a search interface.
index.jsp: The dynamic results page that renders weather data and executes JavaScript for icon switching.
style.css: Contains the styling for the container, search bar, and weather details.

⚙️ How to Setup
API Key: Open MyServlet.java and replace "Apni-Api-Key Dalo" with your actual OpenWeatherMap API key.
Server: Deploy the project on an Apache Tomcat server (v9.0 or higher recommended).
Dependencies: Ensure the gson.jar and jakarta.servlet-api.jar are added to your project's build path.
Run: Access the app at http://localhost:8080/Weather_Application_Using_Servlet/index.html.
Developed by: Ahmed Jamal (Inspired by CodingWallahSir)
