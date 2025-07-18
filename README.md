# 🧠 CMOS Full Adder (Transistor-Level Design & Simulation)

A 1-bit full adder designed entirely using **CMOS logic** — implemented and simulated using **LTSpice** at the transistor level. This project explores how basic digital circuits are built from **PMOS and NMOS transistors** without using predefined logic gates.

## ⚙️ What I Built

- A complete 1-bit full adder computing:
  - `Sum = A ⊕ B ⊕ Cin`
  - `Carry = AB + Cin(A ⊕ B)`
- XOR, AND, and OR gates built from scratch using CMOS pull-up/pull-down networks
- Simulated using `VPULSE` inputs to cycle all 8 input combinations
- Verified outputs (`Sum` and `Carry`) match theoretical truth table

## 🔍 Simulation

| A | B | Cin | Sum | Carry |
|---|---|-----|-----|--------|
| 0 | 0 |  0  |  0  |   0    |
| 0 | 0 |  1  |  1  |   0    |
| 0 | 1 |  0  |  1  |   0    |
| 0 | 1 |  1  |  0  |   1    |
| 1 | 0 |  0  |  1  |   0    |
| 1 | 0 |  1  |  0  |   1    |
| 1 | 1 |  0  |  0  |   1    |
| 1 | 1 |  1  |  1  |   1    |

🖥️ **Tools Used**: LTSpice, basic waveform viewer

📁 See `screenshots/` for the waveform and schematic.

---

## 🧠 What I Learned

- Hands-on CMOS logic design (no gate-level abstraction)
- How transistor arrangements implement real logic
- Signal timing, waveform verification, rise/fall behavior
- Functional testing using VPULSE inputs in SPICE

---

## 🚀 Next Steps

- Scale to 4-bit ripple-carry adder
- Design layout in Electric VLSI and run LVS/DRC
- Explore logic optimizations (gate sizing, buffering)

---

## 📜 License

This project is licensed under the MIT License.
