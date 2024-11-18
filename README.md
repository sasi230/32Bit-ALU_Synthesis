## Exp:5 32 Bit ALU-Synthesize the Gate Level Netlist and tabulate Area and Power reports..(Using Genus in Cadence)

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

## Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

## Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic :
![Screenshot 2024-11-18 103233](https://github.com/user-attachments/assets/273baa4c-2996-4c76-b749-0edf916c14b3)

### Area report:
![image](https://github.com/user-attachments/assets/10c04e4c-fa64-4f8a-8e8e-ffac68d02fb5)
### Power Report:
![image](https://github.com/user-attachments/assets/eda16fa9-690b-4783-8780-743c9c189fa3)
## Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
