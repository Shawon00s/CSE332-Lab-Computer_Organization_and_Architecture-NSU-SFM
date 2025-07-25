# 🔬 Lab Report 04  
## 🧪 Design and Simulation of a 3-bit Binary Up-Down Counter

---

## 🎯 Objective
Design and simulate a **3-bit binary up-down counter** using flip-flops and basic logic gates. The goal is to create a counter that can count both upward (incrementing binary values) and downward (decrementing binary values) based on a control signal.

---

## 📘 Reference: Lab Manual

The original lab manual describes the design process for a **4-bit binary up-down counter**, including:
- Theoretical background
- Design approach using JK flip-flops
- Truth table, excitation table, K-maps
- Circuit diagram and waveform analysis

> 📝 *Note: This experiment was adapted to implement a **3-bit** counter instead of 4-bit.*

---

## 📐 Experiment Overview

### ✅ Task Description
> Design and implement a **3-bit binary up-down counter** using JK flip-flops that can:
> - Count from `000` to `111` (up mode)
> - Count from `111` to `000` (down mode)
> - Toggle counting direction based on a control input

---

## 🔁 Truth Table (Simplified)

| Present State | Up = 1 → Next State | Down = 1 → Next State |
|---------------|---------------------|------------------------|
| 000           | 001                 | ---                    |
| 001           | 010                 | 000                    |
| 010           | 011                 | 001                    |
| 011           | 100                 | 010                    |
| 100           | 101                 | 011                    |
| 101           | 110                 | 100                    |
| 110           | 111                 | 101                    |
| 111           | ---                 | 110                    |

---

## 🔧 Design Steps

1. **Determine flip-flop inputs using JK excitation table**
2. **Create Karnaugh maps (K-maps)** for each flip-flop input
3. **Derive simplified Boolean expressions**
4. **Construct logic circuit** using gates and JK flip-flops
5. **Simulate the circuit** to validate up and down counting

---

## 🧮 Flip-Flop Excitation Table

| Q (Current) | Q+ (Next) | J | K |
|-------------|-----------|---|---|
| 0           | 0         | 0 | X |
| 0           | 1         | 1 | X |
| 1           | 0         | X | 1 |
| 1           | 1         | X | 0 |

---

## 🔗 Circuit Diagram

<img src="PNGs/LAB-04_Design of a 3-bit Binary Up-Down counter.png">

---

## 🧪 Simulation Result

The simulation confirms the correct behavior of the counter for both UP and DOWN modes. The output sequence matches the expected binary count, and toggling the control input successfully changes the counting direction.

---

## 📸 Lab Manual Snapshots

<details>
<summary>Click to view images from the Lab Manual (4-bit design reference)</summary>

<img src="PNGs/LAB_Manual-04_Design of a 4-bit Binary Up-Down counter-1.png">
<img src="PNGs/LAB_Manual-04_Design of a 4-bit Binary Up-Down counter-2.png">
<img src="PNGs/LAB_Manual-04_Design of a 4-bit Binary Up-Down counter-3.png">
<img src="PNGs/LAB_Manual-04_Design of a 4-bit Binary Up-Down counter-4.png">
<img src="PNGs/LAB_Manual-04_Design of a 4-bit Binary Up-Down counter-5.png">
<img src="PNGs/LAB_Manual-04_Design of a 4-bit Binary Up-Down counter-6.png">

</details>

---

## 📓 Lab Report Images

<details>
<summary>Click to view handwritten lab report scans</summary>

<img src="PNGs/LAB_Report_04-Design of a 3-bit Binary Up-Down counter-1.png">
<img src="PNGs/LAB_Report_04-Design of a 3-bit Binary Up-Down counter-2.png">
<img src="PNGs/LAB_Report_04-Design of a 3-bit Binary Up-Down counter-3.png">
<img src="PNGs/LAB_Report_04-Design of a 3-bit Binary Up-Down counter-4.png">
<img src="PNGs/LAB_Report_04-Design of a 3-bit Binary Up-Down counter-5.png">
<img src="PNGs/LAB_Report_04-Design of a 3-bit Binary Up-Down counter-6.png">
</details>

---

## ✅ Conclusion

The design and simulation of a **3-bit binary up-down counter** was successfully completed using JK flip-flops. The circuit responded correctly to the control input, demonstrating proper up-counting and down-counting sequences. This experiment solidified understanding of sequential logic and flip-flop excitation.

---
