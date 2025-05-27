# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2025-05-27 at 11 01 44_4578fed9](https://github.com/user-attachments/assets/bb37f813-3152-42ee-bc27-d49e4a1cbd7b)


Area report:
![WhatsApp Image 2025-05-27 at 11 01 44_fb1b1ffe](https://github.com/user-attachments/assets/42b14633-6908-41e7-9d5e-284740717c65)


Power Report:
![WhatsApp Image 2025-05-27 at 11 01 43_23cd4aa8](https://github.com/user-attachments/assets/4dcd88a8-b659-4c4b-b61d-9a651e438a50)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
