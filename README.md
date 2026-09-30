# Smart-Essentials-iot
Software-based IoT prototype for tracking essential items, managing schedules, and providing location-based reminders using MQTT, RFID, GPS, cloud storage, and object-location tracking.


## Concept 5 – Software-Based IoT Prototype

### Problem Statement

People often forget to carry essentials or misplace them while traveling from one place to another.

### Project Overview

Smart Essentials is a software-based IoT prototype designed to help users manage and track their essential items while moving between different locations.

The system combines schedule-based essential lists, inventory logging, object-location tracking, cloud storage, location-based reminders, and MQTT communication.

### Concept 5 Features

- **User Location:** Inbuilt GPS Module in electronics
- **List of Essentials:** Acquired Listing based on schedule
- **Object Location:** Air Tags
- **Inventory Logging:** Active RFID logging
- **Inventory Data Storage:** Cloud Storage
- **Identify Position of Missing Object:** Relative Positioning
- **Alerts and Reminders:** Location based reminders
- **Communication:** MQTT
- **Power Source:** Battery

### Virtual Prototype

The current prototype is a software-first interactive web application.

The prototype includes:

- Dashboard
- My Essentials
- Find an Item
- My Schedule
- Alerts & Reminders
- IoT & MQTT
- How It Works

The prototype uses simulated IoT inputs to demonstrate the intended system workflow.

### System Workflow

1. Sense
2. Communicate
3. Process and understand
4. Determine the required action
5. Notify the user
6. Help the user locate or recover the missing item

### IoT and Communication

MQTT is used as the proposed communication protocol between the IoT system and the software application.

The proposed physical implementation can integrate:

- ESP32-class IoT controller
- GPS module
- RFID reader
- RFID tags
- Object-location tags
- Rechargeable battery
- MQTT broker
- Cloud database/backend

### Prototype Status

This is a **software-based virtual prototype**.

GPS, RFID, object-location and MQTT inputs are represented through simulated data in the current prototype. These components can be integrated during the physical proof-of-concept stage.

### Future Scope

- Real GPS integration
- Real RFID inventory detection
- Real object-location tracking
- MQTT broker integration
- Cloud database integration
- Mobile application
- Improved location-based notifications
- Battery and power optimization

### Project Details

**Project:** Smart Essentials IoT System  
**Concept:** Concept 5  
**Prototype Type:** Software-Based IoT Virtual Prototype
