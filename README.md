# 🤖 Pick and Place Robotic Arm – Medsby Internship

This project was created as part of a short-term internship at **Medsby Healthcare & Engineering Solutions**. It features a 4-DOF robotic arm controlled via both potentiometers and GUI-based serial commands.

## 📌 Overview
- Built with Arduino Uno and MG90S servo motors
- Controlled manually via 10kΩ potentiometers
- GUI/Serial input fallback for remote operation
- Entire frame 3D printed with PLA
- Power managed using a buck converter (5V/2A)

## 👨‍💻 Team Members
- **Suriya Kumar S** – SRM IST KTR  
- **Shakthi Dharan RV** – SRM IST KTR  
- **Sharvesh S** – SRM IST KTR  

## 🔧 Components Used

### Electrical
- Arduino UNO
- 4× MG90S Servo Motors
- 4× 10kΩ Potentiometers
- Buck Converter
- Breadboard, Jumper Wires

### Mechanical
- 3D Printed Arm Parts (PLA)
- Screws, Bolts

## ⚙️ Features
- Dual-mode control (manual + serial)
- Smooth servo motion using interpolation
- Gripper angle limitation (60°–150°)
- Analog input smoothing with low-pass filter

## 📂 Files Included
- `PROJECT_REPORT.docx` – Full report of the project  
- `Arduino_Code.ino` – Sketch for controlling the robotic arm  
- `images/` – Photos or diagrams of the project (optional)  
- `GUI/` – (Optional) Serial control GUI in Python (if added later)

## 🚀 Getting Started
1. Upload `Arduino_Code.ino` to your Arduino Uno.
2. Connect potentiometers to analog pins A0–A3.
3. Connect servos to digital pins D5, D6, D9, D10.
4. Power using a 5V/2A supply through a buck converter.
5. Optionally, send serial commands (e.g., `B90,S45,E120,G60`) for GUI control.


## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

