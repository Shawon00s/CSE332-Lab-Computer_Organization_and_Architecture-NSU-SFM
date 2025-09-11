# 🖥️ CSE332 Lab: Computer Organization and Architecture

[![Course](https://img.shields.io/badge/Course-CSE332-blue.svg)](https://github.com/Shawon00s/CSE332-Lab-Computer_Organization_and_Architecture-NSU-SFM)
[![University](https://img.shields.io/badge/University-NSU-green.svg)](https://nsu.edu.bd/)
[![Digital Design](https://img.shields.io/badge/Tool-Logisim-orange.svg)](http://www.cburch.com/logisim/)

This repository contains comprehensive lab materials, circuit designs, and documentation for the **CSE332 Computer Organization and Architecture** course at **North South University**. Each lab focuses on fundamental concepts of digital logic design, computer architecture, and processor design using hands-on circuit simulation.

---

## 📚 Course Overview

**CSE332** is a core computer science course that explores the fundamental concepts of computer organization and architecture. Through practical laboratory exercises, students gain hands-on experience in:

- **Digital Logic Design** - Basic logic gates, combinational circuits
- **Arithmetic Units** - Binary arithmetic operations and ALU design
- **Sequential Circuits** - Counters, state machines, and memory elements
- **Processor Components** - Register files, datapaths, and control units
- **Computer Architecture** - Instruction set architecture and processor design

---

## 🧪 Laboratory Experiments

This repository contains **7 comprehensive laboratory experiments**, each with detailed documentation, circuit files, and simulation results:

### [🔗 Lab 01: Design of a 2-bit Logic Unit](LAB-01_Design%20of%20a%202-bit%20Logic%20unit/)
**Objective:** Design and simulate a 2-bit logic unit capable of performing basic bitwise operations (AND, OR, XOR, NOT) using multiplexer-based function selection.

**Key Concepts:**
- Combinational logic design
- Boolean algebra and truth tables
- Multiplexer implementation
- Function selection using control signals

---

### [🔗 Lab 02: Design of a 2-bit Arithmetic Unit](LAB-02_Design%20of%20a%202-bit%20Arithmetic%20unit/)
**Objective:** Implement a 2-bit arithmetic unit supporting addition, subtraction, increment, and decrement operations using IC components.

**Key Concepts:**
- Binary arithmetic operations
- IC 7483 (4-bit binary adder)
- IC 74F153 (Dual 4-to-1 multiplexer)
- Carry and borrow handling

---

### [🔗 Lab 03: Design of a 3-bit by 3-bit Binary Multiplication Unit](LAB-03_Design%20a%203-bit%20by%203-bit%20Binary%20Multiplication%20Unit/)
**Objective:** Design and implement a 3×3 binary multiplication unit using shift-and-add algorithm with logic gates and binary adders.

**Key Concepts:**
- Binary multiplication algorithms
- Partial product generation
- Multi-level adder networks
- Combinational multiplier design

---

### [🔗 Lab 04: Design of a 3-bit Binary Up-Down Counter](LAB-04_Design%20of%20a%203-bit%20Binary%20Up-Down%20counter/)
**Objective:** Design a 3-bit synchronous binary counter capable of counting up or down based on a control signal using JK flip-flops.

**Key Concepts:**
- Sequential circuit design
- JK flip-flop excitation tables
- State transition diagrams
- Karnaugh map minimization
- Synchronous counter design

---

### [🔗 Lab 05: Design of a Register File](LAB-05_Design%20of%20a%20Register%20File/)
**Objective:** Design and simulate a 16-bit wide register file supporting read and write operations for a simplified instruction set architecture.

**Key Concepts:**
- Register-level storage
- ISA specification (R-type, I-type, J-type)
- Read/write control logic
- Address decoding and selection

---

### [🔗 Lab 06: Design of an ALU](LAB-06_Design%20of%20an%20ALU/)
**Objective:** Design and simulate a 16-bit Arithmetic Logic Unit (ALU) by cascading 1-bit ALU units with overflow detection and zero flag functionality.

**Key Concepts:**
- ALU architecture and design
- Arithmetic operations (Add, Subtract)
- Logical operations (AND, OR)
- Overflow detection
- Status flag generation

---

### [🔗 Lab 07: Build a Single Cycle Datapath](LAB-07_Build%20a%20single%20cycle%20datapath/)
**Objective:** Construct a single-cycle datapath for R-type instructions, integrating ALU, register file, and control logic.

**Key Concepts:**
- Processor datapath design
- Instruction execution cycle
- Control signal generation
- Component integration

---

## 🛠️ Tools and Technologies

### Primary Design Tool
- **[Logisim](http://www.cburch.com/logisim/)** - Digital logic simulator used for all circuit designs and simulations
  - Version: Latest stable release
  - Platform: Cross-platform (Windows, macOS, Linux)
  - File extension: `.circ`

### Hardware Components (Physical Labs)
- **IC 7404** - Hex Inverter
- **IC 7483** - 4-bit Binary Adder
- **IC 74F153** - Dual 4-to-1 Multiplexer
- **Trainer Boards** - For physical implementation and testing

---

## 📁 Repository Structure

```
CSE332-Lab-Computer_Organization_and_Architecture-NSU-SFM/
├── README.md
├── LAB-01_Design of a 2-bit Logic unit/
│   ├── README.md
│   ├── LAB-01_Design of a 2-bit Logic unit.circ
│   ├── LAB_Manual-01_Design of a 2-bit Logic unit.pdf
│   ├── LAB_Report_01-Design of a 2-bit Logic unit.pdf
│   └── PNGs/
├── LAB-02_Design of a 2-bit Arithmetic unit/
│   ├── README.md
│   ├── LAB-02_Design of a 2-bit Arithmetic unit.circ
│   ├── LAB_Manual-02_Design of a 2-bit Arithmetic unit.pdf
│   └── PNGs/
├── LAB-03_Design a 3-bit by 3-bit Binary Multiplication Unit/
│   ├── README.md
│   ├── LAB-03_Design a 3-bit by 3-bit Binary Multiplication Unit.circ
│   ├── LAB_Manual-03_Design a 3-bit by 3-bit Binary Multiplication Unit.pdf
│   ├── LAB_Report_03_Design a 3-bit by 3-bit Binary Multiplication Unit.pdf
│   └── PNGs/
├── LAB-04_Design of a 3-bit Binary Up-Down counter/
│   ├── README.md
│   ├── LAB-04_Design of a 3-bit Binary Up-Down counter.circ
│   ├── LAB_Manual-04_Design of a 3-bit Binary Up-Down counter.pdf
│   ├── LAB_Report_04_Design of a 3-bit Binary Up-Down counter.pdf
│   └── PNGs/
├── LAB-05_Design of a Register File/
│   ├── README.md
│   ├── LAB-05_Design of a Register File.circ
│   ├── LAB_Manual-05_Design of a Register File.pdf
│   ├── LAB_Report_05_Design of a Register File.pdf
│   └── PNGs/
├── LAB-06_Design of an ALU/
│   ├── README.md
│   ├── LAB-06_Design of an ALU.circ
│   ├── LAB_Manual-06_Design of an ALU.pdf
│   ├── LAB_Report_06_Design of an ALU.pdf
│   └── PNGs/
└── LAB-07_Build a single cycle datapath/
    ├── README.md
    ├── LAB-07_Build a single cycle datapath.circ
    ├── LAB_Manual-07_Build a single cycle datapath.pdf
    ├── LAB_Report_07_Build a single cycle datapath.pdf
    └── PNGs/

```

**Each lab directory contains:**
- 📄 **README.md** - Comprehensive lab report with objectives, design steps, and results
- ⚙️ **.circ files** - Logisim circuit implementations
- 📚 **PDF manuals** - Official lab instructions and student reports
- 🖼️ **PNGs folder** - Circuit diagrams, simulation screenshots, and lab manual images

---

## 🚀 Getting Started

### Prerequisites
1. **Install Logisim**
   - Download from: http://www.cburch.com/logisim/
   - Ensure Java is installed on your system
   - Follow installation instructions for your operating system

2. **Basic Knowledge Required**
   - Digital logic fundamentals
   - Boolean algebra
   - Binary number systems
   - Basic computer architecture concepts

### How to Use This Repository

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Shawon00s/CSE332-Lab-Computer_Organization_and_Architecture-NSU-SFM.git
   cd CSE332-Lab-Computer_Organization_and_Architecture-NSU-SFM
   ```

2. **Navigate to Specific Labs**
   - Each lab is in its own directory
   - Start with LAB-01 and progress sequentially
   - Read the README.md in each lab for detailed instructions

3. **Open Circuit Files**
   - Double-click `.circ` files to open in Logisim
   - Or use: File → Open in Logisim

4. **Follow Lab Instructions**
   - Read the lab manual (PDF) for theoretical background
   - Follow the README.md for implementation details
   - Use the provided circuit as reference or starting point

---

## 📖 Learning Outcomes

Upon completion of these laboratories, students will be able to:

- ✅ **Design combinational logic circuits** using basic gates and multiplexers
- ✅ **Implement arithmetic operations** in digital systems
- ✅ **Create sequential circuits** including counters and state machines
- ✅ **Build processor components** such as ALUs and register files
- ✅ **Understand computer architecture** fundamentals and datapath design
- ✅ **Use digital design tools** effectively for circuit simulation
- ✅ **Apply Boolean algebra** and optimization techniques
- ✅ **Integrate multiple components** into complex digital systems

---

## 📝 Assessment and Reports

Each lab includes:
- **Pre-lab preparation** - Study the lab manual and theoretical concepts
- **Circuit implementation** - Design and simulate using Logisim
- **Testing and verification** - Validate functionality with test cases
- **Lab report** - Document design process, results, and analysis
- **Post-lab questions** - Demonstrate understanding of concepts

---

## 🎓 Course Information

- **Course Code:** CSE332
- **Course Title:** Computer Organization and Architecture
- **Institution:** North South University (NSU)
- **Faculty:** [Dr. Md. Shafiul Alam](https://www.du.ac.bd/faculty/faculty_details/EEE/1168)
- **Level:** Undergraduate
- **Prerequisites:** CSE231 (Digital Logic Design)

---

## 👥 Contributing

This repository serves as an educational resource. If you're a student in this course:

1. **Use as Reference** - Learn from the implementations and documentation
2. **Report Issues** - If you find errors or have suggestions for improvement
3. **Follow Academic Integrity** - Use for learning, not direct copying
4. **Share Knowledge** - Help fellow students understand concepts

---

## 📞 Contact & Support

For questions related to:
- **Course Content** - Contact your lab instructor or TA
- **Repository Issues** - Create an issue on GitHub
- **Logisim Problems** - Refer to official Logisim documentation

---

## 📜 License & Academic Use

This repository is created for educational purposes as part of the CSE332 course at NSU. All lab materials and designs are based on the official course curriculum and lab manuals.

**Academic Integrity Notice:** Students should use this repository as a learning resource and reference. Direct copying without understanding violates academic integrity policies.

---

## 🏆 Acknowledgments

- **North South University** - For providing excellent laboratory facilities
- **Course Instructors** - For comprehensive lab manuals and guidance
- **Logisim Development Team** - For creating an excellent educational tool
- **Fellow Students** - For collaborative learning and knowledge sharing

---

**🎯 Ready to start? Begin with [Lab 01: Design of a 2-bit Logic Unit](LAB-01_Design%20of%20a%202-bit%20Logic%20unit/) and work your way through the complete computer organization journey!**
