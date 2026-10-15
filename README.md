# 🌃 Automatic Street Light Control System Using Combinational Logic And Gray to Binary Code Converter

## 📌 Project Overview

This project focuses on the design and simulation of an **Automatic Street Light Control System using Combinational Logic**.

The system automatically controls a street light based on the given input conditions. Digital logic concepts such as **truth tables, Boolean expressions, and logic gates** are used to design and simulate the system.

---

## 🎯 Problem Statement

Traditional street lights may require manual operation or may remain switched on unnecessarily, leading to inefficient energy usage.

This project aims to design an automatic street light control system using **combinational logic** that determines whether the street light should be switched **ON or OFF** based on the input conditions.

---

## ⚙️ Methodology

The project was developed using the following steps:

1. Identify the input and output conditions.
2. Create a truth table for all possible input combinations.
3. Derive the Boolean expression.
4. Implement the Boolean logic using logic gates.
5. Simulate and verify the circuit.

---

## 🧠 Working Principle

The system receives input conditions and processes them using a combinational logic circuit.

* **Output = 1:** Street Light ON 💡
* **Output = 0:** Street Light OFF

The output is generated according to the Boolean expression derived from the truth table.

---

## 🛠️ Tools Used

* Logisim
* Tinkercad
* GitHub

---

## ✨ Concepts Used

* Combinational Logic
* Boolean Algebra
* Truth Tables
* Logic Gates
* Digital Circuit Design

---

## 📂 Repository Contents

This repository contains the files related to the project, including:

* `README.md` – Project overview and documentation
* Logic circuit simulation files
* 3D simulation files
* Supporting project documentation

---

## 🚀 Future Scope

The project can be further developed into a real-world smart street lighting system by integrating:

* Light sensors
* Motion or vehicle detection sensors
* Microcontrollers
* IoT-based monitoring
* Energy-efficient lighting systems

---
# Gray to Binary Code Converter

## 📌 Project Overview
The **Gray to Binary Code Converter** is a digital logic project that converts Gray code into its equivalent binary code. Gray code is a binary numbering system in which two consecutive values differ by only one bit, helping reduce errors during digital transitions.

## 🎯 Objectives
- Understand Gray code and binary code.
- Implement Gray-to-binary conversion logic.
- Learn the applications of code converters in digital electronics.

## ⚙️ Conversion Logic
The conversion follows these rules:

1. The most significant bit (MSB) of binary is the same as the MSB of Gray code.
2. Each subsequent binary bit is obtained by XORing the previous binary bit with the current Gray code bit.

**Formula:**

- `B[MSB] = G[MSB]`
- `B[i] = B[i+1] XOR G[i]` (when reading bits from left to right, each binary bit is the previous binary bit XOR the current Gray bit).

**Example:**

| Gray Code | Binary Code |
|---|---|
| `000` | `000` |
| `001` | `001` |
| `011` | `010` |
| `010` | `011` |
| `110` | `100` |
| `111` | `101` |
| `101` | `110` |
| `100` | `111` |

## 🛠️ Technologies Used
- Digital Logic Design
- XOR logic gates
- Gray and binary code conversion principles

## 🔄 Working Principle
1. Take the Gray code as input.
2. Copy the most significant bit directly to the binary output.
3. XOR each subsequent Gray bit with the previous binary bit.
4. Combine the resulting bits to obtain the equivalent binary code.

## 📚 Applications
- Digital communication systems
- Rotary encoders and position sensors
- Analog-to-digital conversion systems
- Digital electronic circuits

## 🚀 Future Improvements
- Support for different input bit lengths.
- Implement the converter using Verilog or VHDL.
- Develop a simple graphical interface for input and output.


## 👥 Team Members

* **Srikari Attaluri**
* **Yagnapriya**
* **Akshith**
* **Vishwam**
* **Surya Deva Teja**
---

## 📚 Conclusion

This project demonstrates the practical application of **combinational logic in automation systems**. By using Boolean logic, truth tables, and logic gates, an automatic system for controlling street lights can be designed and simulated effectively. The Gray to Binary Code Converter successfully converts Gray code into its equivalent binary code using XOR logic, demonstrating an important concept in digital electronics.
