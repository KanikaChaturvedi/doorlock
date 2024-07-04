# IoT-Based Smart Biometric Door Lock System

## Project Overview
This project involves the development of an IoT-based smart biometric door lock system that enhances security through biometric verification. The system stores user data on a campus network database and uses email for verification and notifications.

## Features
- **Biometric Authentication**: Uses fingerprint or facial recognition for door access.
- **Database Storage**: All user data and access logs are stored securely on the campus network.
- **Email Verification**: Sends verification emails for access requests and alerts.

## Components
- **Hardware**:
  - R307 Biometric sensor (fingerprint scanner or facial recognition camera)
  - ESP32 Wifi Board
  - Door lock mechanism (uses a standard servo)
  - SD Card and Reader
    

- **Software**:
  - The project is based on an ESP32 architecture connected to an enterprise network, (IITK) in the current implementation.



### Software Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/smart-biometric-doorlock.git
   cd smart-biometric-doorlock
