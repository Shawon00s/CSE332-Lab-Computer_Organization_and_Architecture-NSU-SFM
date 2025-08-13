# 🔬 Lab Report 06  
## 🧪 Design and Simulation of an Arithmetic Logic Unit (ALU)

---

## 🎯 Objective
Design and simulate a **16-bit Arithmetic Logic Unit (ALU)** capable of performing both arithmetic and logical operations. The ALU will be built by combining multiple 1-bit ALU units and will include additional functionalities such as overflow detection and equality check (zero signal).

---

## 📘 Reference: Lab Manual

The lab manual covers:
- Concept of an ALU and its role in the CPU
- Step-by-step construction of a 1-bit ALU
- Expansion to a 16-bit ALU by cascading 1-bit ALUs
- Implementation of arithmetic operations (Add, Sub) and logical operations (AND, OR)
- Integration of overflow detection and zero signal

---

## 📝 Task Description
> Implement a **16-bit ALU** in Logisim that:
> 1. Performs arithmetic operations: **Addition** and **Subtraction**
> 2. Performs logical operations: **AND** and **OR**
> 3. Supports **overflow detection**
> 4. Supports **zero signal (equality check)**
> 5. Uses a modular design by creating a 1-bit ALU subcircuit and replicating it

---

## 📜 ISA Specification

- **R-type:** `op (4 bits)` `rs (4 bits)` `rt (4 bits)` `rd (4 bits)`
- **I-type:** `op (4 bits)` `rs (4 bits)` `rt (4 bits)` `immediate (4 bits)`
- **J-type:** `op (4 bits)` `Target (12 bits)`

---

## ⚙️ ALU Functional Specifications

**Inputs:**
- A (16-bit operand)
- B (16-bit operand)
- Cin (1-bit carry input)

**Outputs:**
- S (16-bit result)
- Cout (1-bit carry output)
- Zero flag (1 if result = 0)
- Overflow flag (1 if signed overflow occurs)

**Supported Operations:**
- Addition (`A + B`)
- Subtraction (`A - B`)
- Logical AND (`A & B`)
- Logical OR (`A | B`)

---

## 🔧 Design Steps

1. **Design the 1-bit ALU**:
   - Implement the logic diagram in Logisim
   - Label all inputs, outputs, and selection lines
   - Verify basic operations (Add, AND, OR)
2. **Add subtraction** capability to the 1-bit ALU
3. **Build the 16-bit ALU** by cascading 16 copies of the 1-bit ALU
4. **Implement overflow detection** using sign bit logic
5. **Implement zero detection** using equality check logic
6. **Test and verify** for all operations

---

## 🖥️ Circuit Diagram

<img src="PNGs/LAB-06_Design of an ALU.png" />

---

## 🧪 Simulation Result

The simulation confirmed:
- Correct results for all arithmetic and logical operations
- Proper overflow flag behavior for signed overflow cases
- Zero signal activation when output result is all zeros

---

## 📸 Lab Manual Snapshots

<details>
<summary>Click to view images from the Lab Manual</summary>

<img src="PNGs/LAB_Manual-06_Design of an ALU-1.png" />  
<img src="PNGs/LAB_Manual-06_Design of an ALU-2.png" />  
<img src="PNGs/LAB_Manual-06_Design of an ALU-3.png" />  
<img src="PNGs/LAB_Manual-06_Design of an ALU-4.png" />  
<img src="PNGs/LAB_Manual-06_Design of an ALU-5.png" />  

</details>

---

## 📓 Lab Report Images

<details>
<summary>Click to view handwritten lab report scans</summary>

<img src="PNGs/LAB_Report_06-Design of an ALU-1.png" />  
<img src="PNGs/LAB_Report_06-Design of an ALU-2.png" />  
<img src="PNGs/LAB_Report_06-Design of an ALU-3.png" />  
<img src="PNGs/LAB_Report_06-Design of an ALU-4.png" />  
<img src="PNGs/LAB_Report_06-Design of an ALU-5.png" />  

</details>

---

## ✅ Conclusion

The **16-bit ALU** was successfully designed and implemented in Logisim. The modular design allowed easy scalability from a 1-bit ALU. All arithmetic and logical operations worked correctly, and additional functionalities such as overflow detection and zero flag were integrated and tested. This experiment reinforced the understanding of ALU design and its critical role in CPU operation.

---

