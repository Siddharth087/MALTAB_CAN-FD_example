# MALTAB_CAN-FD_example
This project uses temperature sensor and MBDToolbox in simulink to implement CAN protocol

Step 1: Install MBDToolbox using the following link in MATLAB2017a.
https://nxp.flexnetoperations.com/control/frse/download?element=9501347

You will get a free license after downloading. Save the 'license.dat' file in the lisence folder.

Download the slave and the master simulink model files.

The climate control unit in the car is equipped with a temperature sensor. The engine
temperature is monitored using a temperature sensor.
In our project we have tried to emulate such situations and used 2 evaluation boards to transfer
the temperature from the location to the main control unit. The temperature sensor in use is
Si7021 from Silicon Labs.
The software used to program is Simulink and we have observed the output in FreeMASTER
tool.
The sensor follows I2C protocol and hence we have interfaced the sensor using FlexIO module.
This is a module developed by NXP, and can be configured to obey all serial protocols.
The MBDToolbox developed for Simulink is an excellent tool to learn and understand how CAN
and other protocols work. This toolbox is designed specifically for S32K14x based
development boards.
