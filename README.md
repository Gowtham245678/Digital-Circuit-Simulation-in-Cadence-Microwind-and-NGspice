# Simulation
The project mainly deals with design and performance analysis of a simple 8:1 multiplexer circuit. The circuit is simulated in Cadence,Microwind and NGspice software's. The 8:1 MUX circuit can be generated either using NAND gates or Transmission gates(CMOS).

The Main aim of the project is to get familiar with the below software's.

Cadence provides a wide range of tools for various stages of the electronic design automation (EDA) process, from schematic capture to layout and verification. NGspice is an open-source circuit simulator, i.e it is freely available and can be modified as per user requirements or can be integrated into other tools. Microwind provides an integrated environment for designing and simulating digital and analog circuits, including both CMOS and bipolar technologies.
# Cadence
In this i have used 90nm technolgy files(gdpk90). First I have generated a 2:1 MUX circuit using Transmission gates.
![image](https://github.com/Gowtham245678/Digital-Circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/138134146/ea0a5903-dc05-4cef-81c0-de0284b701aa)

Next, using the above instantiation, 8:1 MUX can be generated.

![image](https://github.com/Gowtham245678/Digital-Circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/138134146/031dd93a-2aca-4495-839b-f4cf7d814808)

Next, Using Analog Design Environment we can simulate our output.

![image](https://github.com/Gowtham245678/Digital-Circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/138134146/2ea1c6ea-850c-4e31-8ab3-5d578a16ab07)

# Microwind
From Microwind, we obtain post layout simulation.I have generated 8to1 MUX using both nand gates and transmission gates by satisfying all the design rules. Now, on comparing Transmission gate circuit uses less area and also generates less delay in the output.

![image](https://github.com/Gowtham245678/Digital-Circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/138134146/2a97e3b2-0d84-4cf2-b8ad-203be8c683c6)

# NGspice
For any digital circuit that is mapped in a circuit it is converted into a netlist which is then used for simulations.

![image](https://github.com/Gowtham245678/Digital-Circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/138134146/d2baa9f2-ebd9-4a53-9eaf-bcb30d71785f)
![image](https://github.com/Gowtham245678/Digital-Circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/138134146/22759111-193e-4f27-a1f5-00c1075aaa80)
















