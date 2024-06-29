# Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice
# Simulation
The project mainly deals with design and performance analysis of a simple 8:1 multiplexer circuit. The circuit is simulated in Cadence,Microwind and NGspice software's. The 8:1 MUX circuit can be generated either using NAND gates or Transmission gates(CMOS).

The Main aim of the project is to get familiar with the below software's.

Cadence provides a wide range of tools for various stages of the electronic design automation (EDA) process, from schematic capture to layout and verification. NGspice is an open-source circuit simulator, i.e it is freely available and can be modified as per user requirements or can be integrated into other tools. Microwind provides an integrated environment for designing and simulating digital and analog circuits, including both CMOS and bipolar technologies.
# Cadence
In this i have used 90nm technolgy files(gdpk90). First I have generated a 2:1 MUX circuit using Transmission gates.
![image](https://github.com/Adish30/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/114245305/4e845e4f-18d5-436d-b0ef-8944eb055ee9)
Next, using the above instantiation, 8:1 MUX can be generated.
![image](https://github.com/Adish30/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/114245305/47a2bd6a-05d7-4619-bbc3-926b64eb7483)
Next, Using Analog Design Environment we can simulate our output.
![image](https://github.com/Adish30/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/114245305/41567c9b-60a3-4c3b-8dd5-fa588d54d7be)
# Microwind
From Microwind, we obtain post layout simulation.I have generated 8to1 MUX using both nand gates and transmission gates by satisfying all the design rules. Now, on comparing Transmission gate circuit uses less area and also generates less delay in the output.
![image](https://github.com/Adish30/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/114245305/9d06bf77-f375-4c24-bb70-0929928b0f32)
# NGspice
For any digital circuit that is mapped in a circuit it is converted into a netlist which is then used for simulations.
![image](https://github.com/Adish30/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/114245305/59afed30-b4a4-468f-a047-7cf7a9ca3637)
![image](https://github.com/Adish30/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/114245305/a0dcba4a-2bb9-4100-8ada-976ef33285cc)
