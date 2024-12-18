
# Traffic_light_controller_Synthesis

**Aim:**

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

**Tool Required:**

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

**Step 1: Getting Started**

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

**Step 2 : Creating an SDC File**

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

** Step 3 : Performing Synthesis**

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

**Synthesis RTL Schematic :**

![Screenshot 2024-11-13 144942](https://github.com/user-attachments/assets/aa552359-c5f1-4ef2-82e5-f72d1b6244eb)

**Area report:**

![Screenshot 2024-11-16 163430](https://github.com/user-attachments/assets/9ade2121-5ade-42c5-8320-b785d15b57fb)


**Power Report:**

![Screenshot 2024-11-16 163536](https://github.com/user-attachments/assets/9eff52de-a7cc-4488-bb21-2bf0b30dc2f9)

**Result:**

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
