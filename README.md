pybcanskin
==========

Basic skin for pyboard with two CAN bus transceivers.
The BOM says that the CAN tranceiver TJA1051T/3 is used.
In the real world I use TJF1051/3, they are pin compatible.

Note that the power the tranceiver comes from Vin in 
the pyboard. This means that you should not supply more than 
5V to the board. Using power from USB works fine. 
