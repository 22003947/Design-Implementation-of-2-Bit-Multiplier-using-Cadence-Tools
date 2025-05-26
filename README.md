## Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![386844548-bfe47e43-607a-4fd4-9f91-3610e32b27bd](https://github.com/user-attachments/assets/2615c171-4282-48c3-abf9-e3d470772714)



## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![386145670-71e954f9-9f3c-4bd0-b5ea-9a9fd11226ee](https://github.com/user-attachments/assets/0f5a582e-a546-4e11-9575-bf0fec5a8601)


![386146336-46ec3836-5b20-4623-9b40-0453f27a09cd](https://github.com/user-attachments/assets/e43a40be-c80d-47d6-8ccf-d6d599110cb0)


### Schematicand Symbol of 2-Input EX-OR Gate:
![386146653-c168141c-7f84-48f1-8291-31ff284ee445](https://github.com/user-attachments/assets/d84f65b4-60ee-4cb6-ba48-7191983017e5)


![386147071-005a8470-c662-46e9-bbf9-8d375491cd6b](https://github.com/user-attachments/assets/1a49dd37-88f3-427f-bf96-c956811f7394)


### Schematicand Symbol of Half Adder:
![386147180-433ba580-ec0a-42b6-8c96-6f1b67b8439e](https://github.com/user-attachments/assets/8cacb9bb-377f-46d2-8e96-f3c0b1712e9f)


![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
![Screenshot 2025-05-10 162446](https://github.com/user-attachments/assets/5b4b78a1-5812-4789-85ec-60324c2b5968)

## Output
### Transient Analysis Output:
![386147348-9254b325-b251-4e49-9eae-f95f05d92b3e](https://github.com/user-attachments/assets/a1e0411a-ebd2-423a-a938-a11e779c2815)


![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


![Screenshot 2025-05-15 152538](https://github.com/user-attachments/assets/694df39e-3505-4cf1-ae99-21bc428300b7)

Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
