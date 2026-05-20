# Arithmetic-Logic-Unit-ALU-Design-in-Logisim
This project implements a manually designed n-bit Arithmetic Logic Unit (ALU) in Logisim Evolution without using built-in ALU components.



## Repository structure

```
ALU-Logisim/
│
├── README.md
├── circuits/
│   └── ALU_project.circ
├── screenshots/
│   ├── ALU_1-bit.png
│   ├── ALU_4-bits.png
│   ├── Arithmetic_Unit.png
│   ├── Arithmetic_Unit_4-bits.png
│   ├── B-logic_unit_1-bit.png
│   ├── B-logic_unit_n-bits.png
│   ├── Carry_Ripple_block_diagram.png
│   ├── Carry_Ripple_detailed_view.png
│   ├── Full_Adder.png
│   ├── Half_Adder.png
│   ├── Logic_Unit.png
│   ├── Logic_Unit_4-bits.png
│   ├── MUX.png
│   └── MUX_4-bits.png
└── 
```

## Components
- Half Adder
- Full Adder
- Ripple-carry adder
- Arithmetic unit
- B-input logic
- Logical unit
- 2:1 multiplexer

## All Supported operations

<img width="424" height="244" alt="General" src="https://github.com/user-attachments/assets/83ad61a0-6d12-4689-98ce-e943fff938f3" />

## Architecture

## 4-bits ALU 

General concept:

<img width="831" height="625" alt="download" src="https://github.com/user-attachments/assets/0d40bda7-78ed-41fd-8ce7-6897265143cf" />

Implementation:

<img width="1200" height="800" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/ALU_4-bits.png" />

## 1-bit ALU

Implementation:

<img width="1200" height="800" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/ALU_1-bit.png" />

## B-logic unit (1-bit and 4-bits)
Supported operations, Truth table, K-map:

<img width="211" height="191" alt="download" src="https://github.com/user-attachments/assets/304287ff-1583-4c2c-952f-ce5e99ff46f3" />
<img width="144" height="229" alt="BLogic_truth_table" src="https://github.com/user-attachments/assets/2754e513-aa33-4c1c-b129-40e0ce7cd56f" />
<img width="197" height="128" alt="BLogic_K-map" src="https://github.com/user-attachments/assets/6b5b66bf-28ac-4255-9f0b-ab8c6a7f8ea3" />

Boolean expression: Y_in = B⋅S0 + ~B⋅S1



Implementation(1-bit):

<img width="800" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/B-logic_unit_1-bit.png" />
(4-bits):
<img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/B-logic_unit_n-bits.png" />

## Arithmetic Unit

Truth table: 

<img width="249" height="240" alt="ArithUnit_truthtable" src="https://github.com/user-attachments/assets/e153dc89-612c-405b-b5ed-21e327215fbd" />

1-bit:

<img width="800" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/Aithmetic_Unit.png" />

The arithmetic unit (4-bits) is implemented using a ripple-carry architecture built from chained full adders.

## Ripple-Carry Adder
General concept:

<img width="777" height="236" alt="download" src="https://github.com/user-attachments/assets/1cac4fe6-2cd8-4227-b43a-fca2671163ad" />

Implementation:

<img width="800" height="600" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/Carry_Ripple_block_diagram.png" />


## Logical Unit 
Supported operations, Truth table, K-map:

<img width="307" height="195" alt="download" src="https://github.com/user-attachments/assets/70029487-d278-4bf3-8ba9-87da2fff3c5b" /> <img width="212" height="190" alt="LogUn_k-map" src="https://github.com/user-attachments/assets/0844ec87-9cd4-49ff-94f3-c1ee934cfc2c" />  <img width="164" height="267" alt="Logical_Unit" src="https://github.com/user-attachments/assets/a504f353-bf9c-457c-89f2-6ed94249dc05" />


Implementation (1-bit and 4-bits):

<img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/Logic_Unit.png" /> <img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/Logic_Unit_4-bits.png" />


## MUX (1-bit and 4-bits)

Truth table, K-map:

<img width="239" height="238" alt="Mux_truth" src="https://github.com/user-attachments/assets/0532b2ff-c1b6-43ab-90ee-c991ec735189" />
<img width="191" height="126" alt="Mux_k-map" src="https://github.com/user-attachments/assets/8c4f2ffa-2459-4f7f-81de-5c0d8e77a71b" />

Boolean expression: G = S2⋅LogUnit+ArUnit⋅~S2

Implementation (1-bit and 4-bits):

<img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/MUX.png" /> <img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/MUX_4-bits.png" />


## Half Adder

<img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/Half_Adder.png" />


## Full Adder

<img width="500" height="300" alt="General" src="https://github.com/PavelVorobevAL/Arithmetic-Logic-Unit-ALU-Design-in-Logisim/blob/main/screenshoots/Full_Adder.png" />

## Technologies

- Logisim Evolution
- Digital Logic Design
- Boolean Algebra

## How to Run

1. Open Logisim Evolution
2. Load alu.circ
3. Simulate the circuit using the input pins



