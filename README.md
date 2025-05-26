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

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![386145670-71e954f9-9f3c-4bd0-b5ea-9a9fd11226ee](https://github.com/user-attachments/assets/976ab97a-1950-4ffd-92b6-8ac84075bd27)

![386146336-46ec3836-5b20-4623-9b40-0453f27a09cd](https://github.com/user-attachments/assets/d150dcc5-e72b-4552-b331-32b76605c4d7)


### Schematicand Symbol of 2-Input EX-OR Gate:

![386146653-c168141c-7f84-48f1-8291-31ff284ee445](https://github.com/user-attachments/assets/f346ede0-b45d-49f6-ad4e-7ed855659899)




### Schematicand Symbol of Half Adder:

![386147071-005a8470-c662-46e9-bbf9-8d375491cd6b](https://github.com/user-attachments/assets/e848c32f-8518-4b7c-adc4-831838c2fdaf)



### Schematic of 2-Bit Multiplier:
![386147180-433ba580-ec0a-42b6-8c96-6f1b67b8439e](https://github.com/user-attachments/assets/c646b091-62f1-4f25-bed6-572d3059124e)


## Output
### Transient Analysis Output:
![386147348-9254b325-b251-4e49-9eae-f95f05d92b3e](https://github.com/user-attachments/assets/399f2fef-1fb7-41df-8240-55c2b41c4084)




Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
