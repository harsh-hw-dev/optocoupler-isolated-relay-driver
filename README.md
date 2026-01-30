# Optocoupler Isolated Relay Driver (PC817 + IRFZ44N)

![Repo Views](https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&repo=optocoupler-isolated-relay-driver&label=Repository%20Views&color=0e75b6&style=flat)

## 📌 Overview
This project demonstrates a **12V relay driver circuit** simulated in **Proteus**, using a **PC817 optocoupler** for electrical isolation and an **IRFZ44N MOSFET** for reliable relay switching.  
The design is suitable for **automation, embedded systems, and industrial control** applications.

---

## 🔧 Features
- Optocoupler-based input isolation (PC817)
- Logic-level control of 12V relay
- IRFZ44N MOSFET low-side switching
- Flyback diode protection for relay coil
- Proteus-ready simulation schematic
- Safe interface between low-voltage MCU and high-voltage load

---

## 🧩 Components Used
- PC817 Optocoupler  
- IRFZ44N N-Channel MOSFET  
- 12V Relay  
- Flyback Diode (1N4007 or equivalent)  
- Resistors (Gate, pull-down, LED current limiting)  
- 12V DC Supply  

---

## ⚙️ Working Principle
1. Input signal drives the PC817 LED.
2. Optocoupler transistor isolates and triggers the MOSFET gate.
3. IRFZ44N switches the relay coil safely.
4. Flyback diode protects against inductive voltage spikes.
5. Relay controls the external AC/DC load.

---

## 🖥️ Simulation
- Software: **Proteus**
- Circuit tested for correct relay operation and isolation behavior.

---

## 📁 Repository Structure

---

## 🚀 Applications
- Industrial automation
- PLC and microcontroller interfacing
- EV charger control circuits
- Home automation systems
- Safe relay driving from GPIO pins

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

## 🤝 Author
**Harsh Saini**  
Hardware Design | Embedded Systems | Power Electronics  

⭐ If you find this useful, give the repo a star!
