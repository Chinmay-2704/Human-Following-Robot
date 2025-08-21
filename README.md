# Human Following Robot 🤖  

This project is a **Human Following Robot Car** built using an **Arduino Motor Driver**, **DC Motors**, **Ultrasonic Sensor**, and **IR Sensors**. The robot detects and follows a human by tracking obstacles in front and using IR sensors to maintain direction.  

---

## 🖼️ Circuit Diagram  
![Circuit](https://github.com/user-attachments/assets/47bf8ecd-4974-4016-9fe8-71e9f56882db)


---

## ⚡ Features  
- Human following using **Ultrasonic Sensor (HC-SR04)**  
- Obstacle detection and avoidance  
- Direction control with **IR sensors (Left & Right)**  
- Smooth movement with **4 DC Motors** and a **Motor Driver Shield**  
- Powered by a **7.4–9V battery pack**  

---

## 🛠️ Components Used  
- Arduino Uno + Motor Driver Shield  
- 4 × DC Motors  
- 1 × Ultrasonic Sensor (HC-SR04)  
- 2 × IR Sensors (Left & Right)  
- 1 × Servo Motor (for ultrasonic sensor rotation)  
- Battery Pack (7.4–9V)  
- Jumper Wires & Switch  

---

## ⚙️ Working Principle  
1. The **Ultrasonic Sensor** mounted on a servo scans the environment to detect the human/object.  
2. The **IR Sensors** on the left and right sides help in maintaining direction and alignment.  
3. The **Motor Driver Shield** controls the four motors, moving the robot forward, left, or right depending on sensor inputs.  
4. If the human moves, the robot detects the change in distance and adjusts accordingly to follow.  

---

