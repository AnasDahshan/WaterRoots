  # 🌱 WaterRoots - Smart Hydroponic Farming System

![WaterRoots Logo](images/WR.png)

## 📌 Project Overview
WaterRoots is a **smart hydroponic indoor/outdoor farming system** that enables users to grow plants in limited spaces. The system integrates IoT technology for control and monitoring via a mobile application. It uses various sensors and actuators to ensure optimal plant growth while providing a user-friendly interface for easy management.

## ✨ Features
- **Automated Hydroponic System**: Uses IoT to monitor and adjust growing conditions.
- **Mobile App**: Provides real-time monitoring and control.
- **Nextion Display Interface**: Local control via a touchscreen interface.
- **Cloud Integration**: Stores and retrieves data from the cloud.
- **Community Forum**: Connects users for discussions and guidance.
- **AI Support**: Chatbot assistance for growing tips.

---

## 📖 Table of Contents
- [System Design](#-system-design)
- [Final Build](#-final-build)
- [Mobile App](#-mobile-app)
- [Nextion Display](#-nextion-display)
- [Video Demo](#-video-demo)
- [Hardware Components](#-hardware-components)
- [Software & Technologies](#-software--technologies)
- [Installation & Setup](#-installation--setup)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🏗 System Design
Below is the full design of the **WaterRoots System**, including structural layout, sensor placement, and flow of operations.

![System Design](PLACEHOLDER_FOR_SYSTEM_DESIGN_IMAGE)

---

## 🏡 Final Build
Here are images of the **final working build** of WaterRoots, showcasing the real-world implementation.

![Final Build - Image 1](PLACEHOLDER_FOR_FINAL_BUILD_IMAGE_1)
![Final Build - Image 2](PLACEHOLDER_FOR_FINAL_BUILD_IMAGE_2)

---

## 📱 Mobile App
The **WaterRoots App** allows users to monitor and control the system remotely. Below are screenshots of various app screens categorized by functionality:

### 1. Sign-In/Sign-Up
Users are welcomed with an intuitive sign-up/login interface. 
- **Firebase Authentication** ensures secure login.
- Supports **Google & Apple SSO** for seamless access.
- Upon authentication, users are directed to the dashboard.

![Sign-Up/Login](PLACEHOLDER_FOR_SIGNUP_SCREEN)

### 2. Home Screen
Provides a **comprehensive system overview** and educational resources.
- Displays **water level, WiFi status, and actuator control**.
- **Educational guides** for pruning, pollinating, and harvesting.
- **Recipe suggestions** based on the user’s harvest.
- **Daily tips** for plant maintenance.

![Home Screen](PLACEHOLDER_FOR_HOME_SCREEN)

### 3. Community Forum
An interactive space where users can **share insights, troubleshoot, and connect**.
- Users can **post images, ask questions, and engage with others**.
- Includes **like, comment, and timestamped post organization**.

![Community Forum](PLACEHOLDER_FOR_FORUM_SCREEN)

### 4. Sprout – AI Chatbot
The AI chatbot assists users with **hydroponic care and troubleshooting**.
- Provides **real-time diagnostics** for nutrient deficiencies, pH levels, and plant diseases.
- Users can **upload images** for analysis and receive actionable insights.

![AI Chatbot](PLACEHOLDER_FOR_CHATBOT_SCREEN)

### 5. System Control (Manual & Auto Mode)
Users can control hydroponic components via **Manual or Auto Mode**.
- **Manual Mode**: Direct control over **grow lights, fans, water pumps, and nutrient pumps**.
- **Auto Mode**: System adjusts **water, nutrients, and climate** autonomously.
- **Live monitoring** of **temperature, humidity, pH, and TDS**.

![System Control](PLACEHOLDER_FOR_CONTROL_SCREEN)

### 6. Garden Section – Plant Growth Tracking
Tracks plant progress from **germination to harvest**.
- Displays **growth stages, plant type, and days to harvest**.
- Provides **actionable tips** for each stage of plant development.
- Features a **progress bar** for visual tracking.

![Garden Section](PLACEHOLDER_FOR_GARDEN_SCREEN)

### 7. User Profile & Settings
Manages user **account settings and preferences**.
- Customizes **profile details and notifications**.
- Enhances **user experience and system personalization**.

![Profile & Settings](PLACEHOLDER_FOR_PROFILE_SCREEN)


---

## 🎛 Nextion Display
The **Nextion Display Interface** provides an alternative local control method for users who prefer a touchscreen setup.

![Nextion Screen 1](PLACEHOLDER_FOR_NEXTION_SCREEN_1)
![Nextion Screen 2](PLACEHOLDER_FOR_NEXTION_SCREEN_2)

---

## 🎥 Video Demo
Watch a full **demonstration** of the WaterRoots system in action:

[![Watch the Video](PLACEHOLDER_FOR_VIDEO_THUMBNAIL)](PLACEHOLDER_FOR_VIDEO_LINK)

---

## 🛠 Hardware Components
The following hardware components are used in this project:

- **Microcontrollers**: Arduino Uno R4, Raspberry Pi
- **Sensors**:
  - pH Sensor
  - Water Level Sensor
  - Electrical Conductivity Sensor
  - Temperature & Humidity Sensor (DHT22)
  - Water Flow Sensor
  - Light Intensity Sensor
- **Actuators**:
  - Water Pump
  - Peristaltic pH Up/Down Pumps
  - Grow Lights
  - Ventilation Fan
- **Display & Connectivity**:
  - Nextion Touch Display
  - Bluetooth & WiFi Module

---

## 💻 Software & Technologies
The project utilizes the following software and frameworks:

- **Mobile App**: Flutter (Dart) + Firebase
- **Embedded Systems**: Arduino C++ + Raspberry Pi Python Scripts
- **Database & Cloud**: Firebase Firestore
- **Web Services**: MQTT for real-time messaging
- **UI & UX**: Nextion Editor for Touch Display UI

---

## 🚀 Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Arduino IDE
- Raspberry Pi OS (for Raspberry Pi)
- Flutter SDK
- Nextion Editor
- Firebase Account (for database storage)

### Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/WaterRoots.git
   cd WaterRoots
   ```
2. **Setup the Arduino Sketch**:
   - Open `waterroots.ino` in Arduino IDE.
   - Select **Arduino Uno R4** as the board.
   - Upload the code.
3. **Run Raspberry Pi Scripts**:
   ```bash
   python3 main.py
   ```
4. **Build & Run the Mobile App**:
   ```bash
   flutter pub get
   flutter run
   ```
5. **Nextion Display Setup**:
   - Open `nextion_ui.hmi` in Nextion Editor.
   - Upload to Nextion Display.

---

## 📝 Usage
- Open the **WaterRoots App** and **sign in**.
- Add your **hydroponic system** to the app.
- Monitor real-time data and control **pumps, lights, and pH settings**.
- Use the **Nextion Touch Display** for quick local control.
- Join the **community forum** for tips and support.

---

## 🤝 Contributing
We welcome contributions to enhance **WaterRoots**! If you’d like to contribute:
- Fork the repository
- Create a new branch (`feature-branch`)
- Commit your changes
- Push to your fork and submit a **Pull Request**

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🚀 **WaterRoots** - Grow Smarter, Not Harder! 🌱
