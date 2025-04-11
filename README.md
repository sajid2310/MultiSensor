# MultiSensor
Create a Multi Sensor for Proximity, Temperature, Humidity, Pressure, Lux &amp; Bluetooth proxy using ESPHOME

I wanted to build a multi sensor largely for my home. In essence the design principles were as follows:
a. The solution must integrate with home assistant - Used ESPHome with Nodemcu devkit v1
b. The solution must detect presenece - Used LD2410C
c. The solution must detect Temperature, Humidity & Pressure - Used BME280
d. The solution must detect Bluetooth Proxy - ESP Home config

Part 1
I started with wiring the breadboard and testing the EPSHOME Configuration (Attached). The schematic is also attached for reference. Was able to integrate the solution using ESPHome in Homeassitant.

Part 2 
I then decided to create a PCB. Used EASYEDA for this. Please find attached ( MultiSensor.zip ) the Gerber files you can upload to any website that will print this for you. I used lion circuit since they were local to India. 

Part 3
Once i tested this for few days started work on 3D printing. Few trial and errors later was able to get to a solution that works for me. Please use the STL files to align the PCB holes (the ones I printed did not have one, since then I added this to the PBC design file. Attached all STL. They are separate files but can be printed together
