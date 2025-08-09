# 🔬 Lab Report 02  
## 🧪 Design and Simulation of a 2-bit Arithmetic Unit

---

## 🎯 Objective
Design and simulate a **2-bit arithmetic unit** as part of an Arithmetic Logic Unit (ALU). The unit should be capable of performing addition, subtraction, increment, decrement, transfer, and their variants with carry/borrow using the given ICs and logic design.

---

## 📘 Reference: Lab Manual

The lab manual provides details for designing a **2-bit arithmetic unit**, including:
- Description of each arithmetic operation
- Function table for operation selection
- Required equipment and IC pin configurations
- Logic diagram and experimental procedure

---

## 📝 Task Description
> Implement a **2-bit arithmetic unit** using IC 7404, IC 7483, and IC 74F153.  
> The unit should be able to:
> - Add two 2-bit inputs  
> - Add with carry  
> - Subtract two inputs  
> - Subtract with borrow  
> - Increment A  
> - Decrement A  
> - Transfer A  

---

## ⚙️ Supported Operations

| S1 | S0 | Cin | Operation               |
|----|----|-----|-------------------------|
| 0  | 0  | 0   | Add                     |
| 0  | 0  | 1   | Add with Carry           |
| 0  | 1  | 0   | Subtract with Borrow     |
| 0  | 1  | 1   | Subtract                 |
| 1  | 0  | 0   | Transfer A               |
| 1  | 0  | 1   | Increment A              |
| 1  | 1  | 0   | Decrement A              |
| 1  | 1  | 1   | Transfer A               |

---

## 🔧 Design Steps

1. **Place ICs** (7404, 7483, 74F153) on the trainer board.
2. **Connect power** (Vcc) and **ground** to each IC.
3. **Wire inputs** to switches and **outputs** to LEDs.
4. Implement the logic diagram as described in the manual.
5. **Test** various input combinations for each operation.
6. **Verify outputs** against the function table.

---

## 🖥️ Circuit Diagram

<img src="PNGs/LAB-02_Design of a 2-bit Arithmetic unit.png">

---

## 🧪 Simulation Result

The circuit successfully performed all required operations as per the function table. Addition and subtraction worked correctly with and without carry/borrow, and increment/decrement operations produced expected outputs.

---

## 📸 Lab Manual Snapshots

<details>
<summary>Click to view images from the Lab Manual</summary>

<img src="PNGs/LAB_Manual-02_Design of a 2-bit Arithmetic unit-1.png">
<img src="PNGs/LAB_Manual-02_Design of a 2-bit Arithmetic unit-2.png">
<img src="PNGs/LAB_Manual-02_Design of a 2-bit Arithmetic unit-3.png">

</details>

---

## ✅ Conclusion

The **2-bit arithmetic unit** was successfully implemented using IC 7404, IC 7483, and IC 74F153. The unit operated correctly for all specified micro-operations, and results matched the theoretical function table. This experiment reinforced the understanding of arithmetic operations within an ALU.

---
