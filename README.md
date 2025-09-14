# 🎤 Voice Based Smart Wheelchair for Physically Impaired Persons

A **Bluetooth-based, voice-operated wheelchair system** designed to improve mobility for people with severe disabilities.  
The system uses an Android app with wireless voice recognition to send movement commands to an **Arduino Uno** via Bluetooth.  
These commands are processed and executed through a **motor driver** that controls the wheelchair’s motors.

---

## ✨ Features
- **Hands-Free Control** – Operated entirely through voice commands.  
- **Wireless Communication** – Bluetooth link between Android app and wheelchair.  
- **Low-Cost Hardware** – Arduino UNO, HC-05 Bluetooth module, L298N motor driver, geared motors.  
- **Expandable System** – Can be enhanced with GPS, solar charging, or even EEG-based control in the future.  

---

## 👥 Team Members
- Mannem Hari Shankar Goud – *220003051*  
- Banoth Santhosh – *230003014*  
- Jaajimoggala Ramaraju – *230003028*  
- Chinthala Prajayvarma – *230003018*  
- S Manjunatha – *230003067*  

---

## 🛠️ Bill of Materials (BOM)

| S.No | Component                  | Qty | Purpose                     | Est. Cost (₹) |
|------|----------------------------|-----|-----------------------------|---------------|
| 1    | Arduino Uno R3 (with cable)| 1   | Microcontroller             | 478           |
| 2    | L298N Motor Driver (2293D) | 1   | Controls DC motors          | 110           |
| 3    | Jumper Wires (40 Pin, 30cm)| As needed | Circuit connections     | 53            |
| 4    | BO Geared Motor            | 2   | Moves wheels                | 272           |
| 5    | Wheels (with motors)       | 2   | Wheel movement              | Included      |
| 6    | Bluetooth Module (HC-05)   | 1   | Android–Wheelchair Link     | 234           |

---

## 🔄 Flow of Operation
1. User speaks a **voice command** into the mobile app.  
2. The app sends the command to the wheelchair via **Bluetooth**.  
3. **Arduino Uno** receives and interprets the command.  
4. Command is passed to the **L298N Motor Driver**, which controls the motors.  
5. Wheelchair moves according to the command (Forward, Backward, Left, Right, Stop).  

---

## 📲 Commands
- **Forward** → Moves wheelchair ahead  
- **Backward** → Moves wheelchair back  
- **Left** → Turns left  
- **Right** → Turns right  
- **Stop** → Stops movement  

---

## 🚀 Future Improvements
- **GPS integration** for navigation and tracking.  
- **Solar charging** for sustainable power.  
- **EEG (brainwave) control** for hands-free, mind-controlled movement.  

---

## 📄 License
This project is developed for academic purposes.  
Open for modification and further research.  



