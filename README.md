# Women Safety Gloves

## Overview

Women Safety Gloves is an IoT-based wearable safety device designed to provide immediate assistance during emergency situations. The system enables users to send SOS alerts along with real-time location information to predefined emergency contacts using GPS and GSM technology. The project aims to improve women's safety by offering a simple, reliable, and easily accessible emergency response solution.

## Features

* Emergency SOS activation through a button press
* Real-time GPS location tracking
* SMS alerts to emergency contacts
* Emergency phone call functionality
* Built-in buzzer alarm for attracting nearby attention
* Portable and wearable design
* Secure communication using encryption concepts
* IoT-based safety monitoring system

## Technologies Used

### Hardware

* Arduino ESP32
* Arduino UNO
* NEO-6M GPS Module
* SIM800L GSM Module
* Buzzer
* Push Button
* Power Supply Module

### Software

* Arduino IDE
* Embedded C/C++
* SMS Notification System
* TinyGPS++ Library
* SoftwareSerial Library

## System Workflow

1. User presses the emergency button.
2. GPS module retrieves the current location.
3. Arduino processes the emergency request.
4. GSM module sends an SMS alert containing location details.
5. The system automatically places a call to the emergency contact.
6. The buzzer activates to attract nearby assistance.

## Project Structure

```text
Women-Safety-Gloves/
│
├── Arduino_Code/
├── Documentation/
├── Circuit_Diagram/
├── Images/
├── README.md
```

## Applications

* Personal Safety
* Women's Security
* Emergency Response Systems
* Smart Wearable Devices
* IoT-Based Safety Solutions

## Future Enhancements

* Real-time cloud connectivity
* AI-based threat detection
* Biometric sensor integration
* Voice activation
* Gesture-based emergency triggering
* Multi-channel alert systems
* Smartwatch integration.
