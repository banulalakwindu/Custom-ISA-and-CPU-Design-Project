# Custom ISA and CPU Design Project

This project involves the design of a custom Instruction Set Architecture (ISA) and the corresponding Central Processing Unit (CPU) to implement that ISA. The project also includes writing an assembly program using the designed ISA and CPU to perform a 3x3 matrix multiplication and calculate the average of the final matrix values.

## ISA Design

### Instruction Types
- R-Type
- I-Type
- J-Type
- K-Type

### Registers
- 16 general-purpose registers

### Instruction Categories
1. **Data Movement**
   - Load/Store operations
   - Register-to-register transfers
2. **Logic**
   - Bitwise AND, OR, NOT
   - Additional logic operations (XOR, NAND, NOR, etc.)
3. **Arithmetic**
   - Addition and Subtraction
   - Optional: Multiplication, Division, Shifting operations
4. **Unconditional Branching**
   - Jump instructions with support for labels and immediate constants

5. **Conditional Branching**
   - Instructions to compare two values and branch based on the result
   - Support for various comparison types (equal to zero, less than zero, greater than zero)

## CPU Design

### Instruction Encoding
- Clearly defined encoding for each instruction type
- Consideration of the 32-bit memory architecture

### CPU Architecture Diagram
- A visual representation of the CPU architecture, including the data path and control unit
- Block diagrams to illustrate the flow of data and control signals

### Control Lines
- Definition of control lines for the CPU design
- Explanation of how control lines are utilized in executing instructions

## Assembly Program

### Matrix Multiplication and Average Calculation
- Description of the assembly program's functionality
- How the program utilizes the ISA instructions to perform the specified task

## How to Run the Assembly Program
1. Load the assembly program into the CPU's memory.
2. Execute the program on the designed CPU.
