
TechNotes 2000



Dark Star Chaos Output Level?

The DSC started out with a 1V or so output level to match most consumer gear. 
Now that it is being used with modular gear, we are advising that the output be raised to the maximum of 3V t
o better match the 10V levels of modular equipment.

This change can be easily done by changing one resistor. 
On Rev 0 boards, change R55 (33K) to 100K. For Rev A boards, change R37 (33K) to 100K.
We are currently shipping assembled units with the 100K resistor installed. 
The kits are being shipped with both resistor values.


Final Filtre Gate Input
It turns out that the FF Gate will not respond to the 5V Gate signals that are the Doepfer standard. 
If you want to use the FF with Doepfer gates, we have a small add-on PCB available 
for installation between the Gate jack and PCB gate connection point. 
This board is available at no charge to current FF owners.

Why your Time Machine may need a slight calibration change
Due to slight variations of the exact voltage of your 15V power supply, 
trim pot RT5 may need to be recalibrated for optimum sound quality. 
Follow the procedure on page 9 of the manual. 
Rotate trim pot RT4 (near the front of the board) FCW for this procedure. (This trimmer sets the audio input level.)

Final Filtre LFO Mod
Some customers want the LFO to run continuously without an external gate or pushbutton activation. 
This is pretty easy to do. Just add a 1K resistor from the unused switch lug on the Gate jack to +15V. 
There are a multitude of feedthrus on the board power buss where this connection can be made.

The LFO can be turned off by switching the LFO/A/D switch to "A/D". 
The A/D will not function.
Inserting a plug into the Gate jack (connected to anything or not) will restore normal operation. 
