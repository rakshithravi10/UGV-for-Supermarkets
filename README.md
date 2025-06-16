# 🤖 UGV for Supermarts – Smart Autonomous Shopping Assistant

An advanced Unmanned Ground Vehicle (UGV) designed to autonomously assist customers inside large hypermarkets. The system intelligently navigates store aisles, identifies obstacles using sensor data, and slows down or stops using **fuzzy logic-based decision making** — making it ideal for helping elderly and differently-abled users shop independently.

---

## 🔍 Project Scope

This UGV was developed as a prototype solution for **indoor last-meter logistics** and **automated cart handling** in smart retail spaces. We conducted extensive site visits across Bengaluru (IKEA, Metro, Reliance Smart) and developed a platform that combines mechanical precision with intelligent behavior.

---

## 🧠 Key Features

- 🚦 **Obstacle Detection with Fuzzy Logic**  
  Infrared (IR) sensors detect objects in proximity. A fuzzy logic controller determines slowdown behavior based on obstacle distance and relative angle.

- 🧭 **Autonomous Navigation Mode**  
  Pre-defined aisle paths with real-time obstacle avoidance using conditional logic.

- 📶 **Bluetooth Manual Override**  
  Integrated mobile interface for switching between autonomous and manual modes.

- 🛠️ **Modular Design**  
  Designed with detachable sensor mounts, interchangeable drive units, and chassis customization support.

---

## 🛠 Technologies Used

| Module | Description |
|--------|-------------|
| 🧠 Microcontroller | Arduino UNO R3 |
| 📡 Sensors | 2x IR Proximity Sensors (front left, right), optional ultrasonic add-on |
| 🧠 Logic | Fuzzy Inference System (implemented in C for Arduino) |
| 💬 Communication | HC-05 Bluetooth module |
| ⚙️ Motor Control | Dual L298N motor driver |
| 🛞 Mobility | 2x 12V DC driver wheels + 2x castor wheels |
| 🔋 Power | 12V 15A Li-Ion battery pack |

---

## 🖼 Visual Showcase

| Assembly | Prototype | Testing |
|----------|-----------|---------|
| ![](images/UGV%20Final%20Assembly.png) | ![](images/UGV%20Prototype.png) | ![](images/UGV%20Prototype%20Testing.png) |

> Parts Overview: [Driver Wheels](images/Driver%20wheels.png), [Castor Wheels](images/Castor%20Wheels.png), [Chassis](images/Chasis.png)

---

## 🧪 System Architecture

[ IR Sensors ] ---> [ Fuzzy Controller ] ---> [ Motor Speed Output ]
|
Distance, Angle → Decision Rules → PWM Output


---

## 📄 Documentation

- [📘 Project Summary Report (PDF)](documents/Grp12-UGV-ppt.pdf)

---

## 🚀 Potential Extensions

- Real-time vision system for aisle tracking  
- Path planning using SLAM (Simultaneous Localization and Mapping)  
- ROS2 integration and Gazebo simulation  
- Object pick-and-place using robotic arm attachment  
- Fleet coordination for multi-UGV cart handling

---

## 🙌 Credits

**Developed by:**  
Rakshith R, Shashank M A, S. Hitesh, Sumanth S Kundapur  
**Guided by:** Mr. Shivaramu L  
**Institution:** Dept. of Mechanical & Manufacturing Engineering, India

---

> 💬 _“Designed for real-world challenges. Powered by fuzzy logic, built by curiosity.”_

