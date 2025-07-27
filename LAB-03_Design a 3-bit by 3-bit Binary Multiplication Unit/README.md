# 🔬 Lab Report 03  
## 🧪 Design and Simulation of a 3-bit by 3-bit Binary Multiplication Unit

---

## 🎯 Objective
Design and simulate a **3-bit by 3-bit binary multiplication unit** that takes two 3-bit binary inputs and produces a 6-bit binary product. The design involves generating partial products and summing them using binary adders.

---

## 📘 Reference: Lab Manual

The original lab manual describes the design of a **4-bit by 4-bit binary multiplication unit**, covering:
- Theory of binary multiplication
- Structure of partial products
- Use of adders for summing
- Block diagram and circuit implementation

---

## 📝 Task Description
> Design a **3-bit by 3-bit binary multiplier** using logic gates and binary adders.  
> The multiplier should take two 3-bit binary numbers as input and output a 6-bit binary product.

---

## ✍️ Binary Multiplication Logic

- Binary multiplication follows the same rules as decimal multiplication, using shifts and additions.
- A 3-bit by 3-bit multiplier involves:
  - Generating 3 rows of partial products
  - Aligning and adding them using **half adders** and **full adders**

---

## 🔧 Design Steps

1. **Generate partial products** using AND gates  
2. **Align rows** according to bit significance  
3. **Use half/full adders** to sum partial products  
4. **Build the circuit** using logic gates and adder components  
5. **Simulate and verify** the output for all combinations

---

## 🔢 Example

For inputs:  
`A = 101` (5)  
`B = 011` (3)  
Expected output:  
`A × B = 1111` (15 in binary)

---

## 🧪 Simulation Result

The simulation confirmed that the 3×3 multiplier produced correct results for all possible input combinations. Partial products and adder combinations were verified step-by-step.

---

## 📸 Lab Manual Snapshots

<details>
<summary>Click to view images from the Lab Manual (4×4 design reference)</summary>

<img src="PNGs/LAB_Manual-03_Design a 4-bit by 4-bit Binary Multiplication Unit-1.png">
<img src="PNGs/LAB_Manual-03_Design a 4-bit by 4-bit Binary Multiplication Unit-2.png">
<img src="PNGs/LAB_Manual-03_Design a 4-bit by 4-bit Binary Multiplication Unit-3.png">
<img src="PNGs/LAB_Manual-03_Design a 4-bit by 4-bit Binary Multiplication Unit-4.png">
<img src="PNGs/LAB_Manual-03_Design a 4-bit by 4-bit Binary Multiplication Unit-5.png">

</details>

---

## ⚠️ Important Note
Although the lab manual provides instructions for a **4-bit by 4-bit multiplier**, we were clearly instructed during the lab session to implement a **3-bit by 3-bit multiplier**.  
However, **one of my groupmates mistakenly prepared the lab report using the 4×4 design instead of the required 3×3 version**. The circuit simulation and actual implementation were done correctly with 3-bit inputs.

---

## 📓 Lab Report Images

<details>
<summary>Click to view handwritten lab report scans</summary>

<img src="PNGs/LAB_Report_03-Design a 3-bit by 3-bit Binary Multiplication Unit-1.png">
<img src="PNGs/LAB_Report_03-Design a 3-bit by 3-bit Binary Multiplication Unit-2.png">
<img src="PNGs/LAB_Report_03-Design a 3-bit by 3-bit Binary Multiplication Unit-3.png">
<img src="PNGs/LAB_Report_03-Design a 3-bit by 3-bit Binary Multiplication Unit-4.png">
<img src="PNGs/LAB_Report_03-Design a 3-bit by 3-bit Binary Multiplication Unit-5.png">

</details>

---

## 🖥️ Circuit Diagram

<img src="PNGs/LAB-03_Design a 3-bit by 3-bit Binary Multiplication Unit.png">

---

## ✅ Conclusion

The **3-bit by 3-bit binary multiplication unit** was successfully designed and simulated using logic gates and binary adders. The final circuit performed accurate multiplication for all input combinations. Despite the confusion in the written report referring to a 4×4 multiplier, the actual implementation and simulation were done correctly based on the 3×3 specification as instructed in the lab.

---
