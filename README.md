# 🎙️ Pre-amplifier for Spy Microphone 

## 📘 Project Overview
This project was carried out as part of the **1A Bureau d'Étude d'Électronique (Electronics Design Project)** at **Grenoble INP – Phelma**, during the first semester of the **Physics, Electronics and Telecommunications (PET)** engineering program.

The objective was to design and implement a **pre-amplifier for an electret microphone**, which could be later connected to an FM transmitter.  
I completed **Tiroir 2**, which includes the following functional blocks:
- Microphone biasing and pre-amplification
- Adjustable volume control
- Sound detection via a LED indicator

All circuits were powered under **asymmetrical supply (0–5 V)** and implemented using **MCP6002 operational amplifiers**.

---

## ⚙️ Features (Tiroir 2)
- **Electret Microphone Biasing** — converts the small current variations from the microphone into voltage.  
- **Variable Gain Amplifier** — amplifies weak audio signals with adjustable sensitivity.  
- **Volume Control** — allows amplitude adjustment before the output stage to avoid distortion.  
- **Sound Detection LED** — implemented with a comparator with hysteresis to indicate when a sound is detected.  
- **Power Supply:** 0 – 5 V (single supply)  

---

## 🧠 Design and Implementation
- Circuit **designed and simulated in KiCad**
- **Component sizing** based on theoretical transfer functions and Bode plots  
- **PCB routing** performed in KiCad, ensuring clean signal paths and proper grounding  
- **PCB manufacturing** followed by **manual soldering** and **experimental validation**  
- Tested using **oscilloscope** and **function generator** to verify:
  - Correct biasing
  - Amplification gain and frequency response
  - Proper LED threshold behavior

---

## 📷 Project Images

### 🖋️ Schematic Diagram  
> ![Schematic Placeholder](./images/schematic.png)

### ⚡ PCB Layout (Design in KiCad)  
> ![PCB Layout Placeholder](./images/pcb_design.png)

### 🔩 Printed PCB (Before Soldering)  
> ![Bare PCB Placeholder](./images/pcb_bare.png)

### 🔧 Assembled Board (After Soldering)  
> ![Assembled PCB Placeholder](./images/pcb_soldered.png)

---

## 🧩 Components Used
| Component | Description | Note |
|------------|--------------|------|
| MCP6002 | Dual Operational Amplifier | 0–5 V single-supply compatible |
| Electret Microphone | Audio input sensor | Requires biasing resistor |
| Resistors / Potentiometers | Gain and volume adjustment | E12 standard series |
| LED + Comparator | Sound level indicator | Implemented with hysteresis |
| Capacitors | AC coupling and filtering | 50 Hz–20 kHz bandpass design |

---

## 📊 Results
- Clean and stable amplification of the audio signal  
- Adjustable output amplitude via volume potentiometer  
- Reliable LED indication of detected sound  
- Measured gain and frequency response consistent with theoretical predictions  

---

## 🧰 Tools and Environment
- **Software:** KiCad, LTSpice, Oscilloscope interface tools  
- **Hardware:** Breadboard, 0–5 V power supply, Function generator  
- **Programming Language:** None (pure analog circuit)  

---

## 📚 Acknowledgments
Project supervised by:
- **Nicolas Ruty**
- **Fanny Poinsotte**
- **Matthieu Guerquin-Kern**

Grenoble INP – Phelma, 1A PET (Tronc Commun)

---

## 🧾 License
This project is part of an academic exercise at Grenoble INP – Phelma.  
You are free to use the design for educational purposes with proper credit.

---

© 2024 Marc Fikry
