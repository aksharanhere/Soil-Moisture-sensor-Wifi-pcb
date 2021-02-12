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
> It can measure any liquid

> No corrosion Problem

> Wide range of O/p for different values of Water level

> Highly reliable and Efficient
 
# PCB Description
> Works for any Analog/Digital reading.Sensitivity can be altered accordingly.Can be easily linked through wifi with the help wemos D1 mini pro.
# Designed using EasyEDA, Can Order from JLCPCB/NextPCB
> [EasyEDA Project Link Here](https://easyeda.com/aksharan.g/soil-moisture-sensor)

>[Gerber Files](https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/Gerber_PCB_2021-02-10_23-38-45_2021-02-12.zip)

> [Order from JLCPCB](https://jlcpcb.com/)

> [Order from NextPCB](https://www.nextpcb.com/)

This PCB is designed using EasyEDA which is an easy to use PCB design tool.
JLCPCB.com and NextPCB is a well known PCB manufacaturer wherein we can order quality PCBs at low prices. Once the PCB is designed using EasyEDA, we can easily order the PCB from JLCPCB.

# Circuit / sensor(probe) / LM393 ic

> Circuit
<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/Rain-Sensor-Circuit-Diagram.png">
</p>

> sensor
<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/probe.png">
</p>

> LM393 ic
<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/lm393-pinout-datasheet-equivalent.jpg">
</p>

# Schematic

> Wifi enabled Analog/digital reading sensor module 

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/Schematic_Soil%20Moisture%20Sensor_2021-02-11%20(1).png">
</p>

# Pcb Design
> This is a Santa's Rein deer themed Creative Board

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/bottom_layer.png">
</p>

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/Top_Layer.png">
</p>

<p align="center">
<img align="center" src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/both_combined.png">
</p>


# 3D Model
<p align="center">
<img align="center"src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/3dmain1.png">
</p>

<p align="center">
<img align="center"src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/3dside1.png">
</p>

<p align="center">
<img align="center"src="https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/Back3d.png">
</p>

# BOM 
> [Bill of Material](https://github.com/aksharanhere/Soil-Moisture-sensor-Wifi-pcb/blob/main/BOM_Soil%20Moisture%20Sensor%20wifi_2021-02-12.csv)


