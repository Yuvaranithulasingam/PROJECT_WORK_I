# REAL TIME LCOHOL DETECTION AND INTELLIGENT VEHICLE TRACKING FRAMEWORK WITH IOT ENABLED DASHBOARD AND GSM ALERT MECHANISM

## INTRODUCTION :

The Real-Time Alcohol Detection System is designed to identify alcohol influence using a combination of sensor-based detection (MQ-3 Alcohol Sensor) and intelligent alerting mechanisms. The system continuously monitors the driver's breath using the alcohol sensor and immediately triggers alerts if the alcohol level crosses the permissible threshold. This solution aims to reduce drink-and-drive accidents by detecting intoxication early and notifying the responsible authorities or family members.
The project also integrates a real-time IoT dashboard and GSM module to send SMS alerts, making the system suitable for smart vehicle safety applications.

## SCOPE OF THE PROJECT :

This project focuses on developing an embedded and IoT-enabled solution capable of:</BR>
     - Monitoring alcohol levels in real time using a sensitive gas sensor.</BR>
     - Alerting the user and authorities when alcohol levels exceed the threshold.</BR>
     - Locking/controlling the vehicle ignition based on alcohol readings.</BR>
     - Providing continuous data visualization through an IoT dashboard.</BR>
     - Ensuring safety in personal vehicles, school buses, taxis, logistics fleets, and emergency vehicles.</BR>
The scope extends to both hardware integration (sensors, microcontroller, GSM module) and software implementation (Streamlit dashboard, database logs, real-time updates).</BR>

## FEATURES :

1. Real-Time Alcohol Detection using MQ-3 or equivalent sensor</BR>
2. Instant GSM Alerts to emergency contacts</BR>
3. Vehicle Ignition Control (optional) to prevent drunk driving</BR>
4. Live IoT Dashboard showing alcohol level trends</BR>
5. Buzzer/LED Alerts when threshold is breached</BR>
6. Compact embedded system suitable for all vehicles</BR>

## USAGES :

This system can be used in:</BR>
🚗 Personal Vehicles – Prevent drivers from operating vehicles under alcohol influence</BR>
🚌 School Buses – Ensures the driver isn't intoxicated before duty</BR>
🚕 Taxi / Ride Services – Safety measure for passengers</BR>
🚚 Logistics & Fleet Vehicles – Companies can monitor driver safety</BR>
🚑 Emergency Vehicles – Ensures responsible driving by staff</BR>
🏭 Industries – Workers operating heavy machinery can be monitored.</BR>
User-friendly web interface (optional Streamlit/Flask dashboard)</BR>
Low-cost and highly efficient safety mechanism</BR>

## SYSTEM ARCHITECTURE :

<img width="845" height="529" alt="image" src="https://github.com/user-attachments/assets/efcaa234-4b0d-4a2c-896f-4e4457ea3937" />

## WORK FLOW :

### 1. Alcohol Detection
The MQ-3 alcohol sensor continuously monitors the surrounding air and measures the alcohol concentration level.

### 2. Signal Processing
The sensor output (analog voltage) is read by the microcontroller (Arduino/ESP32).
The values are processed to determine if they cross the pre-set threshold.

### 3. Decision Making
If alcohol level > threshold:
  - Trigger buzzer + LED alert
  - Send data to IoT dashboard
  - Notify via GSM message
  - Disable vehicle ignition (optional)

### 4. Data Transmission
The microcontroller sends data to the cloud/IoT dashboard for real-time monitoring.

### 5. Dashboard Visualization
The Streamlit or cloud dashboard displays alcohol levels, system status, alerts, and logs.

### User Alerts
   - SMS alert to registered mobile numbers
   - Real-time dashboard popups
   - Audible buzzer warning inside vehicle

## TECHONOLOGIES USED :

### Hardware Technologies:

1. MQ-3 Alcohol Sensor
2. Arduino / ESP32 Microcontroller
3. GSM Module (SIM800/SIM900)
4. Buzzer and LED Indicators
5. Jumper wires, resistors
6. Power supply module

### Software Technologies:

1. Arduino IDE (for microcontroller programming)
2. Serial communication (UART)
3. Embedded C for Arduino.

## CIRCUIT IMPLEMENTATION :

<img width="533" height="332" alt="image" src="https://github.com/user-attachments/assets/2a3739ab-6a48-4601-b457-36127f6afaa3" />

## OUTPUT :

The Real-Time Alcohol Detection System provides continuous monitoring of alcohol levels and displays the live readings through the IoT dashboard or serial interface. When the alcohol concentration remains within the safe range, the system indicates a normal status. If the alcohol level crosses the threshold, the system immediately triggers a buzzer and LED alert, sends an SMS notification to the registered mobile number through the GSM module, and optionally disables vehicle ignition for safety. The dashboard updates in real time, showing warning messages, status indicators, and a graph of alcohol level variations. All sensor readings and alert events are recorded in the system logs, enabling easy tracking and analysis of driver safety conditions.

<img width="589" height="307" alt="image" src="https://github.com/user-attachments/assets/86689e78-6a84-4e4f-a4fd-9e3950492012" />

<img width="220" height="376" alt="image" src="https://github.com/user-attachments/assets/ce3e87ed-7e8d-483a-aa05-3499357bdc38" />

## RESULT :

The Real-Time Alcohol Detection System successfully detects alcohol concentration with high accuracy and responds instantly when unsafe levels are identified. The system reliably triggers audible and visual alerts, sends automated SMS notifications through the GSM module, and updates the IoT dashboard in real time. The microcontroller processes sensor data smoothly and ensures immediate action, such as warning the driver or preventing vehicle ignition if required. The dashboard displays clear readings, warning messages, and logs, proving the system’s effectiveness in monitoring and preventing alcohol-influenced driving. Overall, the project achieves its objective of enhancing vehicle safety by providing a fast, low-cost, and dependable alcohol detection solution.
