pybcanskin
==========

Basic skin for pyboard with two CAN bus transceivers.
The BOM says that the CAN tranceiver TJA1051T/3 is used.
In the real world I use TJF1051/3, they are pin compatible.

Note that the power the tranceiver comes from Vin in 
the pyboard. This means that you should not supply more than 
5V to the board. Using power from USB works fine. 

Link to PCB at OSH park
<a href="https://oshpark.com/shared_projects/ZzbDCTR0"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
