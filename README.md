# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. Schematic of Full Custom 2:1 MUX
*![image]![Screenshot 2025-04-08 183753](https://github.com/user-attachments/assets/1eb0fc0c-4993-4a57-ab20-74bb14c2e321)

### 2. Transient Response Setup

*![image]![Screenshot 2025-04-08 184556](https://github.com/user-attachments/assets/b35648cd-da41-45ec-ad5f-27d6fb5176a0)



![image]![Screenshot 2025-04-08 184708](https://github.com/user-attachments/assets/f2ea66d8-5b9e-4cbf-80c5-c3e8da3731c9)


## Output

### 1. Transient Analysis Output
*![image]![Screenshot 2025-04-08 184100](https://github.com/user-attachments/assets/8583d635-768d-4d57-9233-daac28c908e1)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
