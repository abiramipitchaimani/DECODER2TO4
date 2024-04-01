# DECODER2TO4


## AIM:
To simulate and synthesis decoder using Xilinx ISE.
## APPARATUS REQUIRED: 
Xilinx 14.7 Spartan6 FPGA
## PROCEDURE: 
### STEP:1 
Start the Xilinx navigator, Select and Name the New project.
### STEP:2 
Select the device family, device, package and speed. 
### STEP:3 
Select new source in the New Project and select Verilog Module as the Source type.
### STEP:4 
Type the File Name and Click Next and then finish button. Type the code and save it. 
### STEP:5 
Select the Behavioral Simulation in the Source Window and click the check syntax. 
### STEP:6 
Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
### STEP:7 
Select the Implementation in the Sources Window and select the required file in the Processes Window.
### STEP:8 
Select Check Syntax from the Synthesize XST Process. Double Click in the Floorplan Area/IO/Logic-Post Synthesis process in the User Constraints process group. UCF(User constraint File) is obtained.
### STEP:9 
In the Design Object List Window, enter the pin location for each pin in the Loc column Select save from the File menu.
### STEP:10 
Double click on the Implement Design and double click on the Generate Programming File to create a bitstream of the design.(.v) file is converted into .bit file here.
### STEP:11 
Load the Bit file into the SPARTAN 6 FPGA
### STEP:12 
On the board, by giving required input, the LEDs starts to glow light, indicating the output.
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)
# PROGRAM:
```
SUBMITTED BY
P.ABIRAMI
212222060006
```
```
module decoder_1(a,b,c,y);
input a,b,c;
output[7:0]y;
endmodule
```
# OUTPUT:
![Screenshot 2024-04-01 173606](https://github.com/abiramipitchaimani/DECODER2TO4/assets/163704307/e21e5a9b-22fe-4d1c-a8fc-6b2b8d7cbe71)
# RESULT:
Hence, the stimulation and synthesis of a decoder was run successfully by using Xilinx ISE.

