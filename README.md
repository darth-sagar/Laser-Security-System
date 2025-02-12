# Laser Security System using 555 Timer IC  

## 📌 Project Description  
This project is a **Laser Security Alarm System** designed using the **NE555 timer IC** and **LM358 operational amplifier**. The system uses a **laser beam** and a **light-dependent resistor (LDR)** to detect interruptions. If the laser beam is blocked, the buzzer and LED alert the user of an intrusion.  

## 🛠️ Components Used  
- Multipurpose PCB Board  
- **NE555 Timer IC** (configured in monostable mode)  
- **LM358 Op-Amp IC** (used as a comparator)  
- **LM7805 Voltage Regulator IC**  
- Transistor  
- **Photodiode (LDR)** for detecting laser  
- **Resistors**: 10KΩ, 150Ω  
- **10K Potentiometer**  
- **220µF Capacitor**  
- **LEDs** for indication  
- **9V Battery** (Power supply)  
- **Piezo Buzzer** (For alarm)  
- IC Base  
- **Laser Pointer** (Security detection source)  

## ⚙️ Working Principle  
1. **Laser and LDR Setup**:  
   - A laser beam is continuously focused on an **LDR (Light Dependent Resistor)**.  
   - The LDR has **low resistance** when the laser is ON and **high resistance** when blocked.  

2. **Comparator (LM358 Op-Amp)**:  
   - The LM358 **compares** the voltage drop across the LDR and a reference voltage.  
   - If the laser beam is blocked, the op-amp output **switches from HIGH to LOW**.  

3. **Triggering the 555 Timer IC**:  
   - The LOW signal from LM358 triggers the **555 timer IC** (configured in monostable mode).  
   - The **buzzer and LED** are activated for a predefined time to alert of an intrusion.  

## 🖼️ Circuit Diagram  
![Circuit-Diagram](https://github.com/user-attachments/assets/93620647-75a5-4f00-b375-9ebf01ce96d3)
![](https://github.com/user-attachments/assets/696be41a-8720-4415-ba5c-c3a5b3335ace)

## 📌 Applications  
✅ **Home Security** – Can be used to secure doors and windows.  
✅ **Bank Vaults** – Detect unauthorized entry.  
✅ **Museums & Art Galleries** – Prevents unauthorized access to restricted areas.  
✅ **Industrial Security** – Can be integrated into automation systems.  

## Video 
 ![Video](https://github.com/darth-sagar/Laser-Security-System/blob/main/Media/VID_20230117_020643.mp4)


