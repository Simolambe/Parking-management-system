# Parking-management-system
A software for Smart Parking System with Mobile Wireless Chargers for Electric Vehicles

LINK TO THE DIRECTORY THAT CONTAINS THE FRONTEND: https://drive.google.com/drive/folders/1hXLtp5zJwbVQuKi8EvkRuc_ygW1AJd9j?usp=sharing

Key Features:
User Types:

Basic users: Access parking and request charging services.
Premium users: Can reserve parking spots in advance and receive additional privileges.
Administrator: Monitors the system, manages parking rates, and oversees parking spot occupancy and payments.
MWbot Functionality: MWbots can identify vehicle models, calculate battery capacities, and autonomously charge cars by moving between them. Once a vehicle reaches the desired charge level, the MWbot moves to the next car in line.

User Interactions:

Basic and Premium Users: Can request charging, view the queue of cars to be charged, and accept or decline the estimated waiting time.
Notifications: Users receive alerts when their vehicle reaches the desired charge level.
Premium Users: Can check spot availability, reserve a spot, and manage payments via an app.
Administrator Functions: The admin can monitor parking spot status, update rates, and view payment history, including parking and charging fees for both user types.

System Architecture:
The project is built using microservices architecture with:

Backend (REST API): Manages reservations, parking data, charging services, and payments.
User Interface: A cross-platform app or web interface allowing users to interact with the backend.
IoT Subsystem Manager: Communicates with parking spot sensors, MWbots, and other hardware components through MQTT messaging.
The system includes core functionalities such as user authentication (via OAuth2), real-time updates on parking availability, and a queue management system for vehicle charging. Optional components include external payment gateways and multi-MWbot support.

This project was collaboratively developed by a team of three students, with each team member responsible for different subsystems and features.
