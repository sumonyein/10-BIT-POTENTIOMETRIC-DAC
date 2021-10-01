# 10-BIT-POTENTIOMETRIC-DAC
The goal of the project is to create a 10-bit Potentiometric Digital to Analog Converter utilising open-source EDA tools from start to finish Using simulation tools such as eSim and ngspice to use the sky130nm technology.
# The Function of a Digital to Analogue Converter (DAC)
 Analog to digital converters and digital to analogue converters are the two types of converters available. These two conversion interfaces are required for a processor to perform the required actions on data from digital electronic and analogue electric devices. A digital to analogue converter (DAC) converts digital data into an analogue signal that can be used to interact with the real world. A binary code, which is a combination of bits 0 and 1, is used to represent a digital signal. A microcontroller, Field Programmable Gate Array (FPGA), or Application Specified Integrated Circuit (ASIC) can generate the digital data (ASIC). The weighed resistors approach and the R-2R ladder network method are the two most popular DAC conversions. Audio amplifiers, video encoders, display electronics, data gathering systems, calibration, and digital potentiometers are all examples of DAC applications.
# Simulations and Pre-layout designs
These simulations were carried out using the following tools:

eSim \sngspice
In eSim, the schematics for a switch circuit and a 2 bit DAC were created.
The implementation of a switch design and its associated waveform are shown below:

![Screenshot 2021-09-30 150641](https://user-images.githubusercontent.com/91714449/135608409-5236ebf0-53c7-470c-a204-7ba2f466ce0e.png)
![Screenshot 2021-09-30 163521](https://user-images.githubusercontent.com/91714449/135609237-7fb66ca2-c70f-4880-808b-fd27f303fe08.png)
![Screenshot 2021-10-01 181115](https://user-images.githubusercontent.com/91714449/135644230-1208aa99-b6d2-4e1e-b8a5-6861879eaab5.png)
# 2 bit DAC
A switch circuit was included as a subcircuit for the 2 bit DAC. The spice netlist was extracted after the schematics were created. The necessary model files of sky130 tt transistors were included in the netlist and transient analysis was performed.

The schematic of 2 bit DAC is as shown below:
![Screenshot 2021-10-01 194126  222](https://user-images.githubusercontent.com/91714449/135649856-5a7bcd2d-97b4-4253-919a-e18ab37d5477.png)
