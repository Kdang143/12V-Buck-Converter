# 12V-Buck-Converter
•	Created a buck converter for Ryerson’s Robotics Club Rover to reduce input voltages of 12-volts to 5-volts output.

•	Utilized datasheets, Eagle Autodesk, and MultiSIM to design an appropriate switch regulator with >80% efficiency.

**Listed Components**

• 1x 100uF Capacitor to deal with input transient voltage noise.

• 1x 1000uF Capacitor to deal with output voltage noise and loop stability

• 1x 100uH Inductor for continous mode operation

• 1x Zener diode to provide a return path for the inductor current when switcher is off

• 1x LM2576-ADJ to allow a adjustabled feedback loop to control the voltage output

**Schematic**

![Screenshot 2021-10-04 234703](https://user-images.githubusercontent.com/68084112/136661787-9dee80e3-075c-423e-9f7e-225b6b90bb73.png)

**Board**\n
![Screenshot 2021-10-04 230539](https://user-images.githubusercontent.com/68084112/136661788-4b964c1f-fbf0-4771-99b7-4bf3e159a272.png)

**Final Product**

![Step Down Voltage Regulator](https://user-images.githubusercontent.com/68084112/136661823-7664201f-181e-4888-85c3-fca45a2bcfd9.png)



