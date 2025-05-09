# 🔌 Adjustable DC Power Supply

An adjustable and regulated **DC power supply** designed using fundamental solid-state electronics. The system steps down and rectifies AC voltage into a variable DC voltage using components such as a transformer, bridge rectifier, LM317 regulator, and smoothing capacitors. 

---

## 🏫 Project Information

* **University:** Benha University, Faculty of Engineering (Shoubra)  
* **Department:** Communications and Computer Engineering  
* **Course:** Solid State Electronic Devices  

---

## 👩‍💻 Team Members

* Abdelrahman Salah El-dein Abdelaziz  
* Mohamed Ahmed Mohamed Hassan  
* Farida Waheed Abdelbary  
* Raneem Ahmed Refaat  

---

## 📌 Project Overview

The system is designed to:

* Convert 220V AC into an adjustable 1.2V–30V DC output.  
* Smooth the rectified voltage using capacitors to minimize ripple.  
* Use an LM317 to regulate and adjust the DC voltage output.  
* Safely interface with electronic circuits or lab equipment.

---

## 🧠 System Features

* **Transformer:** Step-down 220V AC to 24V AC  
* **Bridge Rectifier:** Converts AC to pulsating DC  
* **LM317 Voltage Regulator:** Adjusts output from 1.2V to 30V  
* **Capacitors:** Remove voltage ripple and stabilize output  
* **Potentiometer:** Allows dynamic voltage adjustment  
* **LED:** Power indicator  
* **Banana Jacks:** Output terminals  
* **Switch & Plug:** For power control and input connection

---

## ⚙️ Components & Values

| Component              | Quantity | Value/Details              |
|------------------------|----------|----------------------------|
| Transformer            | 1        | 24V – 3A                   |
| Bridge Rectifier       | 1        | 100V – 3A                  |
| LM317 Voltage Regulator| 1        | Adjustable 1.2V–37V        |
| Potentiometer          | 1        | 5k                         |
| Resistors              | 2        | 18k (5%), 220Ω (5%)        |
| Capacitors             | 3        | 2200µF, 1µF, 0.1µF (40V)   |
| Diode                  | 1        | 400V – 1A                  |
| LED                    | 1        | Red                        |
| PCB Board              | 1        | Custom fabricated          |
| Switch                 | 1        | ON/OFF rocker              |
| Plug & Cord            | 1        | 2-wire AC plug             |
| Banana Jacks           | 2        | Red and Black              |
| Terminal Block         | 1        | 3-pin                      |
| Soldering Iron         | -        | For PCB assembly           |

---

## 🧾 How It Works

1. **AC Power** enters the system through a plug and switch.
2. The **step-down transformer** reduces 220V to 24V AC.
3. The **bridge rectifier** converts AC to DC.
4. The **capacitors** smooth the rectified voltage.
5. The **LM317** regulates output DC voltage, adjustable via the potentiometer.
6. Output is provided through banana connectors for easy access.

---

## 📐 Circuit Design Steps

1. Design the schematic using Proteus simulation software.
2. Simulate the circuit to verify performance (expected output: 1.25V–29.9V).
3. Print and solder components onto a PCB.
4. Test output using a digital multimeter (actual output: 1.2V–31.5V).
5. Assemble the power supply in a safe and functional enclosure.

---

## 🧪 Testing Results

| Test Case                    | Expected Result                   | Passed |
|-----------------------------|-----------------------------------|--------|
| AC input transformation     | 220V AC ➝ 24V AC                  | ✅     |
| Rectification               | AC ➝ Pulsating DC                 | ✅     |
| Regulation via LM317        | 1.2V–30V output range             | ✅     |
| Smooth DC Output            | Ripple-free constant voltage      | ✅     |
| Load Response               | Stable output under light loads   | ✅     |

---

## 💾 Files Included

* `DC Power Supply.pdf` – Full report of the project
* `DC Power Supply Data Sheet.pdf` – Technical specifications
* `DC Power Supply Presentation.pptx` – Summary slides

---

## 🖼 Circuit Design

* **Simulation Software**: Proteus 8.1  
* **Implementation**: Custom-designed PCB using hand-soldered components

---

## 📷 Screenshots

* Schematic design in Proteus

   ![image](https://github.com/user-attachments/assets/b1f6ebae-e829-411d-b054-82db935a9a8a)
* PCB layout and assembly

  ![image](https://github.com/user-attachments/assets/b279348c-c905-4a60-bfd4-6ec7594a04fb)
* Final product photos

  ![image](https://github.com/user-attachments/assets/35afeb82-d0d8-4acd-a70f-61af7e72b938)
---

## 🛠 Tools Used

* **Proteus 8.1** – Circuit design and simulation  
* **Soldering Tools** – Assembly of PCB  
* **Digital Multimeter (AVO)** – Output testing  
* **PCB Design Software** – Circuit layout and printing
