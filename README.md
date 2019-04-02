# Electromayography-sensor
The following sensor design can amplify, filter &amp; rectify EMG potentials range between less than 50 μV and up to 30 mV  to a 0-3V logic level compatible with arduino's and arm processors inbuilt adc logic level. Open Readme file for more info.

![Circuit Board](https://raw.githubusercontent.com/ohheyitskartik/Electromayography-sensor/master/Images/Board-Image.PNG?token=Au2AXWJlDHDn8pkc8i91U2iUxupQtGBGks5crJ2SwA%3D%3D)

The above mentioned circuit contains :-
1) Differential Op-amp (G=110).
2) Active high pass-filter set at 106.6 Hz.
3) Active low pass-filter set at 1.97 KHz.
4) Active rectification to avoid any damage to your microcontroller from negative voltages.
5) A variable gain at end to control output voltage.

The git contains :- 
- Schematic of the circuit (.Eagle file).
- PCB Design (.Eagle file).
- Parts list with packages and names (.TXT file).
- Images for the breadboard version of the device, PCB design, cad render and output screenshots.

The putput of the device was taken using NI mydaq device - 
Without any muscle movement (placement on forearm).
![output without tiggering the muscle](https://raw.githubusercontent.com/ohheyitskartik/Electromayography-sensor/master/output.PNG?token=Au2AXbc6AfnLe3bbGiwLnSMCa_Cj48Opks5cq0kQwA%3D%3D)

With muscle movement (placement on forearm).
![output with triggering muscle](https://raw.githubusercontent.com/ohheyitskartik/Electromayography-sensor/master/output%20active.PNG?token=Au2AXeq-P-pn4NZZyO-Ng9FizWT_bjrdks5cq0kgwA%3D%3D)
