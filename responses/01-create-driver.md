Let's first define what skills a driver has:
 
* Name
* Age
* Concentration [0,100]
* Motivation [0,100]
* Stamina [0,100]
* Agressiveness [0,100]
* Talent [0,100]
* Overall
 
 
The Overall skill is derived using the following formula:
 
Overall = (Concentration * 3 + Motivation * 3 + Stamina * 3 + Agressiveness + Talent) / 2
 
The Overall should always be stored as an integer and rounded up.
 
Create a structure(s) that would provide easy way to create new drivers, modify existing drivers and delete them.
