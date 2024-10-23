# Temperature-Converter
This project is a simple web-based temperature converter that allows users to convert temperatures between Celsius, Fahrenheit, and Kelvin using HTML, CSS, and JavaScript. It provides a clean, interactive interface for inputting temperatures and instantly seeing the converted results.

#Key Features:

Temperature Input: Users can enter a temperature value in any of the three units: Celsius, Fahrenheit, or Kelvin. The converter will calculate and display the equivalent values in the other two units as soon as the user inputs the temperature.

Real-Time Conversion: JavaScript is used to handle the conversions in real-time. When a user enters a value in one temperature unit, the corresponding values in the other two units are updated automatically without requiring page reloads or button presses.

User-Friendly Interface: The interface is simple and intuitive, featuring input fields for each temperature scale. It is styled using CSS to provide clear labeling and easy navigation.

Error Handling: The application includes basic validation, ensuring that users enter only valid numeric inputs. If the input is invalid, a helpful message is displayed.

Technical Stack:

HTML: Provides the structure of the web page, including input fields for Celsius, Fahrenheit, and Kelvin temperatures, as well as sections for displaying the results.

CSS: Styles the interface, creating a visually appealing and responsive layout that works across different devices.

JavaScript: Manages the core logic of the temperature conversions. When a user enters a temperature, JavaScript functions convert the value between Celsius, Fahrenheit, and Kelvin using the respective formulas:

Celsius to Fahrenheit: F = C × 9/5 + 32

Celsius to Kelvin: K = C + 273.15

Fahrenheit to Celsius: C = (F - 32) × 5/9

Fahrenheit to Kelvin: K = (F - 32) × 5/9 + 273.15

Kelvin to Celsius: C = K - 273.15

Kelvin to Fahrenheit: F = (K - 273.15) × 9/5 + 32


Project Objectives:

To build an interactive temperature converter that updates values in real-time.

To practice JavaScript functions for calculations and DOM manipulation.

To implement user-friendly input fields with proper validation and error handling.

This project is an excellent way to learn about unit conversions and dynamic web applications, offering hands-on experience with basic HTML, CSS, and JavaScript functionality.
