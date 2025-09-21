# Half Adder – PCB Layout (Proteus + ICs)

## 📖 Overview
This project demonstrates a **Half Adder** circuit implemented in **Proteus ARES** as a PCB layout using real ICs.  
The Half Adder adds two 1-bit binary inputs (A and B) and produces two outputs:
- **SUM** → using XOR gate (7486 IC)  
- **CARRY** → using AND gate (7408 IC)  

---

## ⚡ Features
- Hardware implementation using **74xx ICs**:
  - 7486 (XOR gate IC) → SUM output  
  - 7408 (AND gate IC) → CARRY output  
- Inputs applied via DIP switches or header pins.  
- Outputs displayed using **LEDs** with current-limiting resistors.  
- Designed and routed in **Proteus ARES PCB Layout**.  
- Exported schematic and PCB available in **PDF format**.  

---

## 🧩 Circuit Explanation
- Input signals **A** and **B** are connected to both the XOR and AND ICs.  
- The **XOR output** gives the **SUM** bit → connected to an LED.  
- The **AND output** gives the **CARRY** bit → connected to another LED.  
- ICs are powered with **+5V (Vcc)** and **GND**.  
- Resistors are used to limit LED current.  

---

## 📂 Project Structure

