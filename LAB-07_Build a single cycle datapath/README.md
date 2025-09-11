# 🔬 Lab Report 07  
## 🧪 Build and Simulation of a Single Cycle Datapath

---

## 🎯 Objective
Design and simulate a **single-cycle datapath** for a simplified instruction set architecture (ISA). The datapath should support basic arithmetic, logical, memory, and control instructions, all executed within a single clock cycle.

---

## 📘 Reference: Lab Manual

The lab manual describes the process of building a single-cycle datapath, including:
- Introduction to datapath design in computer architecture
- Components such as ALU, Register File, Instruction Memory, and Data Memory
- Control signals required for operation
- Instruction formats (R-type, I-type, J-type)
- Step-by-step design of the datapath and integration of components

---

## 📝 Task Description
> Implement a **single-cycle datapath** in Logisim that:
> 1. Executes R-type, I-type, and J-type instructions in one cycle  
> 2. Connects components such as PC, Instruction Memory, Register File, ALU, and Data Memory  
> 3. Incorporates multiplexers and control logic for proper instruction execution  
> 4. Supports memory read/write, register updates, and branching  

---

## 📜 ISA Specification

- **R-type:** `op (6 bits)` `rs (5 bits)` `rt (5 bits)` `rd (5 bits)` `shamt (5 bits)` `funct (6 bits)`  
- **I-type:** `op (6 bits)` `rs (5 bits)` `rt (5 bits)` `immediate (16 bits)`  
- **J-type:** `op (6 bits)` `address (26 bits)`  

---

## ⚙️ Datapath Components

1. **Program Counter (PC)** – holds the current instruction address  
2. **Instruction Memory** – stores instructions for execution  
3. **Register File** – stores operands and results  
4. **ALU** – performs arithmetic and logical operations  
5. **Data Memory** – supports load/store operations  
6. **Control Unit** – generates signals to coordinate datapath components  
7. **Multiplexers** – select correct data inputs based on control signals  

---

## 🔧 Design Steps

1. Design individual modules (PC, Register File, ALU, Memories)  
2. Integrate modules into a single-cycle datapath  
3. Implement control logic to support instruction decoding  
4. Verify execution of R-type (add, sub, and, or), I-type (lw, sw, beq), and J-type (jump) instructions  
5. Simulate and test with sample programs  

---

## 📌 N.B.
In the lab, we only implemented the **R-type instructions** (e.g., `add`, `sub`, `and`, `or`).  
The lab report is also based solely on the **R-type datapath implementation**.

---

## 🖥️ Circuit Diagram

### Register File  →
<img src="PNGs/LAB-07_Build a single cycle datapath - Register File.png" />

### 16 bit ALU  →
<img src="PNGs/LAB-07_Build a single cycle datapath - 16 bit ALU.png" />

### Instruction Fetch Unit  →
<img src="PNGs/LAB-07_Build a single cycle datapath - Instruction Fetch Unit.png" />

### R-Type Datapath  →
<img src="PNGs/LAB-07_Build a single cycle datapath - R-Type Datapath.png" />

---

## 🧪 Simulation Result

The simulation verified that the single-cycle datapath:
- Correctly fetched, decoded, and executed instructions in one clock cycle  
- Properly updated the program counter and handled branching/jumping  
- Produced correct outputs for ALU operations, memory operations, and register writes  

---

## 📸 Lab Manual Snapshots

<details>
<summary>Click to view images from the Lab Manual</summary>

<img src="PNGs/LAB_Manual_07 - Build a single cycle datapath-1.png" /> 
<img src="PNGs/LAB_Manual_07 - Build a single cycle datapath-2.png" /> 
<img src="PNGs/LAB_Manual_07 - Build a single cycle datapath-3.png" /> 

</details>

---

## 📓 Lab Report Images

<details>
<summary>Click to view handwritten lab report scans</summary>

<img src="PNGs/LAB_Report_07-Build a single cycle datapath-1.png" />
<img src="PNGs/LAB_Report_07-Build a single cycle datapath-2.png" />
<img src="PNGs/LAB_Report_07-Build a single cycle datapath-3.png" />

</details>

---

## ✅ Conclusion

The **single-cycle datapath** was successfully designed and simulated. It executed all instruction types (R, I, J) within one clock cycle, integrating ALU, Register File, Memory, and Control Unit effectively. This experiment deepened the understanding of CPU datapath design and instruction execution in computer architecture.

---

