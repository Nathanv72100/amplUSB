# amplUSB
Simple DIY stereo speaker project built on a perfboard using a PAM8403 amplifier, USB-C 5V power, and a 3.5mm jack

# Source component:
1:USB-C Connector (female) 

2:PAM8403

3:Female port jack

4🔈speakers 3W
(x2)


# Tutorial:


# First step:
Take the PAM8403 available in the provided library. (the main part)
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/46b1733d-34fc-4eee-a283-5b757bfb1f33" />


# second step:
Connect the GND and the shield to the GND on the PAM8403 power supply, and VBUS to VIN.
<img width="1176" height="592" alt="image" src="https://github.com/user-attachments/assets/dd78bf6b-4b43-4e3c-944e-cd60a8581ae8" />

# step three:
Now that this is done, let's wire the AudioPlug connections: T -> L, R -> Ground, and S -> R
<img width="843" height="560" alt="image" src="https://github.com/user-attachments/assets/5facfe8a-b039-42f4-bf72-340d7a335aa4" />

# Final step:
Connect L- and L+ to Speaker 1

Connect R+ and R- to Speaker 2
<img width="834" height="550" alt="image" src="https://github.com/user-attachments/assets/383f6bb3-35ad-442a-aa2c-2e48bcab2867" />

# Result:

Audio Input (AudioPlug):

T ->  L
R -> ⊥
S -> R(PAM8403)

Audio Output:

L- and L+ -> speaker 1

R+ and R- -> speaker 2

Power:

VBUS -> VIN

Shield and GND (4) -> GND (5)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f42ce2fe-8221-4a85-af28-a19a2d04e822" />

The Result is available in "ID".(ID/enceinte.kicad_pro)
