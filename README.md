# 16-bit Comparator Using NAND and NOR Gates
This project demonstrates the design and implementation of a **16-bit magnitude comparator** using only **NAND** and **NOR** logic gates. A magnitude comparator is a combinational circuit that compares two binary numbers and determines their relative magnitudes (greater than, less than, or equal).

## 📚 Table of Contents

- [Project Structure](#-project-structure)
- [Design Methodology](#-design-methodology)
   - [1-bit Comparator](#-1-bit-comparator)
   - [4-bit Comparator](#-4-bit-comparator)
   - [16-bit Comparator](#-16-bit-comparator)
- [Implementation Details](#️-implementation-details)
- [Applications](#-applications)


## 📁 Project Structure

- **`16 bit comparator using nand-nor implementation.pdf`**  
  A comprehensive document detailing the theory, logic design, and implementation process.

- **`project-final/`**  
  Directory containing the comparator design files and related implementation artifacts.

- **`README.md`**  
  Project description and documentation (this file).

---

## 🧠 Design Methodology

The comparator is built in a **hierarchical modular design**, scaled from a basic 1-bit comparator up to a full 16-bit comparator, using only NAND and NOR gates.

### 🔹 1-bit Comparator

Implements basic logic:
- `A > B`: `A AND (NOT B)`
- `A = B`: `(A AND B) OR (NOT A AND NOT B)`
- `A < B`: `(NOT A) AND B`

Implemented using combinations of NAND and NOR logic.

### 🔹 4-bit Comparator

Four 1-bit comparator units are cascaded to compare 4-bit binary values. The logic is extended to account for bit significance, with MSB evaluated first.

### 🔹 16-bit Comparator

Four 4-bit comparator blocks are connected to compare 16-bit numbers. Outputs are merged logically to give final results for:
- A > B
- A < B
- A = B

---

## ⚙️ Implementation Details

- **Only NAND and NOR gates** are used (universal gates).
- Optimized for minimal propagation delay.
- Modular and scalable architecture.
- Includes logic diagrams and circuit schematics in the PDF.

---

## 💡 Applications

Magnitude comparators are commonly used in:
- **ALUs (Arithmetic Logic Units)** – comparison operations in CPUs.
- **Digital Signal Processing** – decision-making circuits.
- **Sorting circuits** – compare and order data efficiently.

---

## 👥 Contributors

- **Osaid Nur**
- **[Moath Wajeeh](https://github.com/SuperMoathx7)**
- **[Ahmad Waleed](https://github.com/3ahma)**


