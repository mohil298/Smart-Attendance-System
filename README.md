Smart Attendance System
Abstract
The Attendance System is a mini-project designed to automate the process of tracking attendance using ESP8266, RFID technology, and a buzzer for audio feedback.
This system can be applied in various scenarios such as educational institutions, workplaces, events, healthcare facilities, and more. 
By leveraging the ESP8266 microcontroller's Wi-Fi capabilities, the system ensures efficient data processing and connectivity, enhancing the accuracy and reliability of attendance tracking.

Project Overview
The attendance system utilizes an ESP8266 microcontroller for processing and Wi-Fi connectivity, an RFID reader for reading RFID cards/tags, and a buzzer for providing audio feedback. 
The system is designed to streamline the attendance process, making it more efficient and less prone to errors.
using HTML,javascript,MySql and php a server and webpage has been created on local server for the backend and to store the attendance

Components
ESP8266 Microcontroller
The ESP8266 is a low-cost Wi-Fi-enabled microcontroller widely used in IoT applications. It provides the necessary processing power and Wi-Fi connectivity for the attendance system.

RFID Reader
An RFID reader module is used to read the unique identification numbers stored on RFID cards or tags. The reader captures the card's ID and sends it to the microcontroller.

RFID Cards/Tags
Each individual is assigned a unique RFID card or tag containing a specific identification number, serving as their attendance marker.

Buzzer
A buzzer connected to the ESP8266 provides audio feedback, emitting different tones or melodies to indicate successful or unsuccessful attendance registration.

Power Supply
The system requires a stable power supply, which can be provided via a USB cable or a battery for a wireless setup.

Importance of Attendance Systems
Attendance systems are essential in various fields for monitoring presence, assessing performance, ensuring security, managing payroll, planning resources, and maintaining compliance. Here are some key fields:

Education: Tracks student attendance, aids in performance assessment, and enhances campus safety.
Workplaces: Facilitates accurate payroll processing, workforce planning, and legal compliance.
Events: Manages access control, participant tracking, and data collection.
Healthcare: Manages patient appointments and ensures regulatory compliance.
Construction/Manufacturing: Enhances safety, project management, and accountability.

System Overview
The attendance system operates by using the ESP8266 to read data from an RFID reader and provide feedback via a buzzer. 
The ESP8266 processes the data, communicates with other components, and can interface with external services for extended functionalities.
then all the details can be accessed and view from the local server and webpage.

This Smart Attendance system has the following features:-

Employees/Users can:

Login with their Username and Password
Mark their attendance through RFID card 
mark thier punch in & out time and stored on local database
Visit their attendance record


Administrators can:

Manage the database and also print and export the details
Add new users/employees data (username/password)
View employee's attendance
access the database and also active users
Check whether employee's attendance was marked or employee was present or absent
