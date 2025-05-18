# Java Weather App

## Overview

I developed a **Java-based Weather App** that provides real-time weather information for any user-specified location. The application fetches data such as temperature, humidity, wind speed, and weather conditions from external APIs, parses JSON responses using **JSON Simple**, and displays the information in a clean, user-friendly graphical interface built with **Java Swing**.

The app architecture includes a launcher, a GUI handler for user input and display, and a backend class responsible for API communication, data processing, and mapping weather codes to readable descriptions.

## Key Technologies & Concepts

- Java Swing for building the graphical user interface  
- JSON Simple library for parsing JSON responses  
- Java’s `HttpURLConnection` for network programming and API communication  
- Modular architecture separating frontend (GUI) and backend (data handling)  

## Features

- Real-time weather updates for any location specified by the user  
- Displays temperature, humidity, wind speed, and descriptive weather conditions  
- Responsive and intuitive GUI for seamless user interaction  
- Robust handling of API data and error conditions  

## What I Learned

- Integrating Java GUI development with live API data  
- Parsing JSON data efficiently using JSON Simple  
- Network programming with Java’s `HttpURLConnection`  
- Designing modular desktop applications combining frontend and backend components  
- Mapping raw weather codes to user-friendly descriptions  

## Getting Started

### Prerequisites

- JDK installed (Java Development Kit)  
- JSON Simple library included in your project classpath  

### Running the Application

1. Clone the repository:


2. Import the project into your favorite Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. Add the JSON Simple library to your project dependencies.

4. Build and run the launcher class.

5. Enter a location in the GUI to fetch and display current weather information.

## Example Usage

- Launch the app and input a city name like "London".  
- The app will display the current temperature, humidity, wind speed, and weather condition description.

## License

This project is licensed under the MIT License.

---

Developed by Ismail Cisse
Building responsive Java desktop applications integrating live API data and rich user interfaces.
