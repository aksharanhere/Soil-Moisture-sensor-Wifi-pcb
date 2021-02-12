# Soil-Moisture-sensor-Wifi-pcb
Here ,we will get to know the different methods to get the analog reading out of any sensor through wifi and even the problems have been put under consideration while building one.

> Problem statement: To create a module for measuring the moisture level of the given soil through capacitance.
 I tried with IC555 and Transistors ,the problem and unreliability we faced were as follows:
# With IC555: 
Here we were changing the frequency of the given input signal with the help
capactitance.So by changing the the value of capacitance ,we got different values of frequency and with the help of F to V converter we got the desired O/p .But the problem here was when the tank was full ,the o/p we got was 3.1 V and when the tank was empty (dry condition ),out o/p was 1.6 V.All this readings are for 3.3 v I/P .So the Bandwidth between the Highest and the lowest value was very small and it was
unreliable to provide this o/p to any Mcu(Arduino/Esp32).
# With Transistors: 
Here the circuit was simple ,we used 4 transistors and got 4 detection values.but the problem here was as the probe were directly going to the water ,  corrosion occurred .this was the main to scrap this idea. That’s the reason we opted for Capacitance as our Prime option.Advantages of using capacitance as water level detection :
# Advantages
o It can measure any liquid
o No corrosion Problem
o Wide range of O/p for different values of Water level
o Highly reliable and Efficient



<p align="center">
<img align="center" src="https://github.com/aksharanhere/Christmas_PCB/blob/main/hp.jpg">
</p>

  
# PCB Description
>The following design is made under the idea of creating a unique christmas decorative board. This can be used as a creative christmas wall art .In this case ,i have designed a Board with "Rein deer (Prancer and vixen)"  theme :)
# Designed using EasyEDA, Can Order from JLCPCB
> [EasyEDA Project Link Here](https://easyeda.com/aksharan.g/christmas)

>[Gerber Files](https://github.com/aksharanhere/Christmas_PCB/blob/main/Gerber_PCB_2020-12-15_10-21-17.zip)

> [Order from JLCPCB](https://jlcpcb.com/)

This PCB is designed using EasyEDA which is an easy to use PCB design tool.
JLCPCB.com is a well known PCB manufacaturer wherein we can order quality PCBs at low prices. Once the PCB is designed using EasyEDA, we can easily order the PCB from JLCPCB.

# Schematic

> 12 Led Arduino nano christmas board

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Christmas_PCB/blob/main/Schematic_Christmas_2020-12-16_02-04-08.png">
</p>

# Design
> This is a Santa's Rein deer themed Creative Board

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Christmas_PCB/blob/main/christPcb.png">
</p>

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Christmas_PCB/blob/main/christPcb1.png">
</p>

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Christmas_PCB/blob/main/christPcb2.png">
</p>


# 3D Model
<p align="center">
<img align="center"src="https://github.com/aksharanhere/Christmas_PCB/blob/main/christ3D.png">
</p>

<p align="center">
<img align="center"src="https://github.com/aksharanhere/Christmas_PCB/blob/main/christ3D1.png">
</p>

<p align="center">
<img align="center"src="https://github.com/aksharanhere/Christmas_PCB/blob/main/christ3D2.png">
</p>
