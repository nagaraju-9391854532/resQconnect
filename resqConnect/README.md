# Crisis Relief Management System

## Overview

The **Crisis Relief Management System** is a web-based platform designed to streamline the coordination between multiple agencies, volunteers, and resources during a crisis or disaster. It enables efficient disaster management through features like volunteer registration, resource tracking, real-time communication, and incident management.

## Features

- *Agency Authentication*: Secure login and registration for agencies and admins.
- *Incident Management*: Automated allocation of incidents to the nearest agency.
- *Volunteer Registration*: Register and manage volunteers for relief operations.
- *Resource Tracking*: Track availability and usage of resources such as medical supplies, food, and shelter.
- *Geolocation Search*: Use radius based search to locate nearby agencies or available resources based on location.
- *Communication Tools*: Integrated with Twilio API for sending real-time SMS alerts to stakeholders.
- *Role-Based Access Control (RBAC)*: Ensures 100% secure access with varying permissions for different stakeholders.

## Technologies Used

- *Frontend*: HTML, CSS, JavaScript, EJS, Bootstrap
- *Backend*: Node.js, Express.js
- *Database*: MongoDB, Mongoose
- *APIs*: Mapbox API (Geolocation), Twilio API (SMS alerts)
- *Authentication*: Bcrypt, Express Sessions, RBAC

## Installation

To set up the project locally, follow these steps:

1. *Clone the repository*:
   ```bash
   git clone https://github.com/AkshithReddy12/crisis-management-and-relief-platform.git
   cd crisis-relief-management-system


2. *Create a .env file in the root directory and add the following variables:*
   ```bash
   TWILLIOSECRET=        # Your Twilio account SID
    TWILLIOAUTHTOKEN=     # Your Twilio Auth Token
    FROMNUM=              # Twilio phone number to send messages from
    FROMEMAIL=            # Email address for sending notifications
    NODEPASS=             # Email account password or app-specific password
    MAPBOX_TOKEN=         # Your Mapbox API access token
3. *Install dependencies*:
   ```bash
   npm install
4. *Run server*:
   ```bash
   node index.js
5. *Go to browser and open*:
    ```bash
    http://localhost:3000/
    

