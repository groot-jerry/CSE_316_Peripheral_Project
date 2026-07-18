# Smart IoT-Based Dustbin

An IoT-enabled smart dustbin that provides **touchless lid operation**, **real-time waste level monitoring**,
and **wireless communication** using Arduino and ESP8266. The system improves hygiene and reduces the need for manual waste inspection.

##  Features

-  Automatic lid opening using an ultrasonic sensor
-  Real-time waste level monitoring via Wi-Fi
-  ESP8266-based IoT connectivity
-  Web-based interface for monitoring and control
-  Full-bin notification system
-  Low-cost and energy-efficient design
-  Reliable sensor calibration for accurate distance measurement

---

## Hardware Components

- Arduino UNO R3
- ESP8266 Wi-Fi Module
- HC-SR04 Ultrasonic Sensor(s)
- Servo Motor (SG90/MG996R)
- Motor Driver (if applicable)
- DC Motors (optional for movement)
- Power Supply/Battery
- Jumper Wires
- Chassis (if mobile version)

---

## Software & Technologies

- Arduino IDE
- C/C++ (Arduino)
- ESP8266 Wi-Fi Library
- HTML/CSS (Web Interface)
- Embedded Systems
- IoT

---

## System Workflow

1. The ultrasonic sensor detects a user's hand.
2. The servo motor automatically opens the lid.
3. After a few seconds, the lid closes automatically.
4. Another ultrasonic sensor monitors the dustbin's fill level.
5. When the dustbin reaches the predefined threshold, the ESP8266 sends the data through Wi-Fi.
6. The web interface displays the current status and notifies the user when the bin is full.

---

##  Circuit Diagram



Arduino UNO
   |
Motor Driver 
   │
   ├── HC-SR04 (Hand Detection)
   ├── HC-SR04 (Waste Level)
   ├── Servo Motor
   └── ESP8266 Wi-Fi Module

---

##  Getting Started

### Clone the Repository

```bash
git clone https://github.com/groot-jerry/CSE_316_Peripheral_Project.git
```

### Upload the Code

1. Open the Arduino project in Arduino IDE.
2. Install the required libraries.
3. Select the correct board and COM port.
4. Upload the sketch.
5. Configure your Wi-Fi SSID and Password.
6. Power the system.

---


## 📈 Future Improvements

- Mobile App Integration
- Cloud Database Support
- Mobile Notifications
- AI-based Waste Classification
- Solar Power Support
- Multiple Bin Monitoring Dashboard

---

**Project Leader**
- Junaed Hossain Jibon

Supervisor
- A S Zaforullah Momtaz (Assistant Professor)

---

## License

This project is developed for academic purposes at the **University of Asia Pacific**.

---

## Acknowledgements

- University of Asia Pacific
- Arduino Community
- ESP8266 Community
- Open Source Contributors
