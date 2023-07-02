# NodeMCU and RFID-RC522 IoT Projects

This repository contains a collection of IoT projects utilizing the NodeMCU board and RFID-RC522 module. These projects demonstrate various applications of the NodeMCU and RFID technology, allowing you to implement your own RFID-based solutions.

## Table of Contents
- [Introduction](#introduction)
- [Projects](#projects)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The NodeMCU is an open-source IoT platform based on the ESP8266 Wi-Fi chip. It provides an easy and cost-effective way to connect devices to the internet and build IoT applications. The RFID-RC522 module is a low-cost RFID reader and writer that operates at 13.56 MHz frequency. By combining the NodeMCU and RFID-RC522, you can create projects that involve RFID tag reading, writing, and interaction with various IoT services.

This repository aims to provide you with a set of example projects that utilize the NodeMCU and RFID-RC522 module to showcase the potential of this combination. Each project comes with detailed instructions, schematics, and code samples to help you get started.

## Projects
1. **Project 1**: RFID Door Lock
   - Description: This project demonstrates how to build an RFID-based door lock system. Users can gain access to a door by scanning a valid RFID tag against the RFID reader. The NodeMCU controls the locking mechanism and authenticates the RFID tags against a predefined list.
   - Features:
     - RFID tag authentication
     - Servo motor control
     - Access control
     - Web-based administration
   - [Project 1 Details](projects/project1/README.md)

2. **Project 2**: RFID Attendance System
   - Description: In this project, an RFID-based attendance system is created using the NodeMCU and RFID-RC522. Students or employees can scan their RFID tags to record their attendance. The system stores the attendance data in a database and provides a web interface for administrators to manage attendance records.
   - Features:
     - RFID tag scanning
     - Attendance tracking
     - Database integration
     - Web-based administration
   - [Project 2 Details](projects/project2/README.md)

3. **Project 3**: RFID Inventory Management
   - Description: This project focuses on creating an RFID-based inventory management system. Each item in the inventory is tagged with an RFID tag, and the NodeMCU reads the tags to track inventory levels. The system provides real-time updates on stock availability and generates alerts for low stock or inventory discrepancies.
   - Features:
     - RFID tag reading
     - Inventory tracking
     - Real-time stock updates
     - Alert notifications
   - [Project 3 Details](projects/project3/README.md)

...

## Requirements
To replicate and run the projects in this repository, you will need the following hardware components:
- NodeMCU development board
- RFID-RC522 module
- Jumper wires
- Breadboard
- Servo motor (for certain projects)
- LEDs and resistors (for certain projects)

Additionally, you should have the following software installed:
- Arduino IDE or any compatible ESP8266 development environment
- Libraries: [MFRC522](https://github.com/miguelbalboa/rfid), [ESP8266WiFi](https://github.com/esp8266/Arduino)

## Installation
1. Clone this repository to your local machine:
   ```
   git clone https://github.com/zoghlamimostafa/NodeMCU-and-RFID-RC522-IoT-Projects.git


   ```

2. Connect the NodeMCU and RFID-RC522 module according to the circuit diagrams provided in each project's folder.

3. Install the necessary libraries in your Arduino IDE or ESP8266 development environment.

## Usage
Navigate to the specific project folder you want to replicate, and follow the instructions provided in the corresponding README file. Each project contains a detailed explanation of the circuit connections, code setup, and usage.

## Contributing
Contributions to this project are welcome. If you have any ideas for improvement or would like to add your own RFID-based project, feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for personal or commercial purposes. See the [LICENSE](LICENSE) file for more details.
