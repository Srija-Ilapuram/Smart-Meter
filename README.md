Smart Meter Application

Project Description

The Smart Meter Application aims to address the issues related to transparent billing processes and raise awareness about electricity consumption. The solution involves implementing a smart meter capable of recording readings at specific intervals and a software application to provide users with insights into their electricity usage. The application calculates various parameters such as voltage, current, instantaneous power, and total power. Additionally, it offers features like monitoring daily consumption, calculating the current bill, and setting and managing a monthly budget.

How to Install and Run the Project

Prerequisites

Arduino IDE with Packages (PZEM004T, ESP8266 Generic Module)
Angular
NodeJs
NPM Manager

Installation Steps

Download the project repository as a zip folder.
Extract the zip folder to your desired location.
Setting Up Arduino IDE
Open the Arduino IDE and install the required packages for PZEM004T and ESP8266 Generic Module.
Load the Arduino code onto the ESP8266 to enable communication with the PZEM004T sensor and send data to the database.

Setting Up Angular Project

Create a new Angular project using the following command:

ng new your-project-name

Copy the contents of the extracted src/app/components and src/app/services folders into the corresponding folders in your Angular project.

Setting Up Server

Create a new folder named server in your project directory.
Copy the server.js file from the extracted src/server folder into the newly created server folder.

Running the Application

In the terminal, navigate to your Angular project directory.

cd your-project-name

Start the Angular application:
ng serve

Open a new terminal and navigate to the server folder.

cd your-project-name/server

Start the server:

node server.js

Open your web browser and go to http://localhost:4200 to access the Smart Meter Application.

Hardware Setup

Connect the PZEM004T Energy Monitoring tool to the ESP8266 MicroController using serial communication.

Configure the ThingSpeak channel by creating an account on MathWorks, logging in to ThingSpeak, creating a channel, and updating the API keys in the code.

How to Use the Project

Monitor Consumption:

Log in to the application and navigate to the dashboard to monitor today's electricity consumption in units and the corresponding bill in rupees.
Set Limits:

Use the set limits feature to input a monthly budget for electricity consumption. The application will calculate day-to-day limits and notify you if exceeded.

Manage Bills:

View and manage your current bill through the web application interface.
Contribution
Contributions to enhance and add features to the Smart Meter Application are welcome. Fork the repository, make your changes, and submit a pull request. Your collaboration will help improve this project and make it more beneficial for users.

Feel free to suggest and implement additional features that can enhance the functionality of the Smart Meter Application. I would love to see your creative contributions! 🌟
