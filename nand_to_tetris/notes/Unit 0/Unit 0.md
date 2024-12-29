




# Hack to Tetris Course Notes

## Unit 0.0: Overview
We will build a complete general-purpose computer through two main courses:
1. **Course 1: Hardware**
2. **Course 2: Software**

![[Pasted image 20241229103706.png]]
### Course 1 Details
- **Duration**: 7 Weeks  
- **Projects**: 6 Projects  
- **Goal**: Build 1 Functional Computer  

---

## Unit 0.1: Introduction
### Key Focus:
- **"What" over "How"**: Focus on abstraction, not implementation.
- **Abstraction**: The essence of programming languages.  

### Responsibility:
- Lower-level details are handled:
  - By someone else
  - Or by you (later or earlier)

### Approach:
- Learn one abstraction layer per week:
  1. Treat lower layers as given.
  2. Implement the higher layer.
  3. Test functionality.  

### Outcome:
By the end of the course:
- Build a fully functioning computer capable of running applications like Tetris.
- Learn abstraction through hands-on implementation.
- Understand the necessities for each development step.

---

## Two-Part Course:
### **Part 1: Hardware**
- **Duration**: 7 Weeks  
- **Focus**: Start with Nand gates and create the HACK computer.

### **Part 2: Software**
- **Duration**: 7 Weeks  
- **Focus**: Start with the HACK computer and build a complete software hierarchy.  

---

## Unit 0.2: The Road Ahead
### Hack Computer Structure:
[ROM <-> CPU <-> RAM] <-> IO Devices

### Big Picture:
From human thought to hardware:  
- High-Level Language -> Compiler -> VM Code -> VM Translator -> Low-Level Code -> Assembler -> Computer Architecture -> Digital Design -> Gate Logic -> Elementary Logic Gates -> Electrical Engineering -> Hardware.  

### Course Focus:
This course covers:
- Low-Level Code
- Assembler
- Computer Architecture
- Digital Design
- Gate Logic
- Elementary Logic Gates
- Hardware

### Building Chips:
- Use a hardware simulator.
- Represent chips as:  
  **Chip Abstraction = HDL Program + Test Script in Simulator**

---

## Weekly Projects:
### Week 1: Elementary Logic Gates
- **Primitive**: Nand  
- **Derived**:  
  - Not, And, Or, Xor  
  - Mux, Dmux  
  - Not16, And16, Or16  
  - Mux16, Or8Way  
  - Mux4Way16, Mux8Way16  
  - DMux4Way, DMux8Way  

### Week 2: Arithmetic and Logic Unit (ALU)
- Half Adder  
- Full Adder  
- Add16  
- Inc16  
- ALU  

### Week 3: Registers and Memory
- Bit  
- Register  
- RAM8, RAM64, RAM512, RAM4k, RAM16k  
- PC  

### Week 4: Writing Low-Level Programs

### Week 5: Computer Architecture
- Memory  
- CPU  
- Computer  

### Week 6: Developing an Assembler

---

## Unit 0.3: From Hack to Tetris
### Programming Outcome (Part 1):
- Write Hack Assembly Code (source language).  
- Translate to Hack Binary Code.  

---
