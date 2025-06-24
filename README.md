# Guitar Talkbox Pedal

# About
The talkbox is one of the most iconic effects that paved the way for some of rock and funks' most unique songs. The talkbox is comprised of a speaker that drives guitar or synth tone through a tube that you then modulate with your mouth to create a "talking" instrument effect. The talkbox was first created in the 1930's by Alvino Rey called the "singing guitar". It was never brought to market at this time, but in the 1960's the idea was revived with the Sonovox for use in cartoons like Tom and Jerry. It was then in the 1970's that rock band guitarists such as Joe Walsh and Peter Frampton started making this device mainstream. With truly unique songs such as Do You Feel Like We Do by Frampton and Rocky Mountain Way by Walsh, this device created a new sound that has never been used before. 

Where the talkbox was used the most was in the rise of funk music through synth and vocals. Used by the likes of Stevie Wonder, Roger Troutman, and Dr. Dre, this also created a truly unique sound that was the face of funk music at the time. 

![158551_0_wide_ver1698055174](https://github.com/user-attachments/assets/6c74358d-2f9e-4396-91fd-a837b5f39fab)

# Parts List
The talkbox itself is pretty simple when it comes to design. As it is just your guitar signal running to a distortion circuit, to a powerful speaker amplifier, to a compression driver that leads to the tube. 

Since I wanted in all-in-one talkbox unit with a distortion circuit, I took a circuit board from my previous [MXR Distortion Plus](https://github.com/codycarter1763/DIY-Distortion-Plus-Pedal) pedal. The difference is I used only silicon diodes instead of germanium diodes for loud and clear distortion. Originally I built a circuit board to install a Bluesbreaker drive pedal, but the distortion was too tame as I wanted to have a heavily distorted signal like a synth's sawtooth wave would have. Such a distorted signal helps with the pronunciation of words and effects with your mouth. 

## Distortion Circuit
- 1 LM741 Op Amp
- 2 1nF Capacitor
- 1 10nF Capacitor
- 1 0.22uF Capacitor
- 2 1uF Capacitors
- 4 1MΩ Resistors
- 1 1KΩ Resistor
- 2 10KΩ Resistors
- 2 1MΩ Log Potentiometer
- 1 10KΩ Log Potentiometer
- 2 1N4001 Silicon Diodes

## Other Parts
- 1 Compression driver, I used a Pyle compression driver from Parts Express that I bought years back. Look for a driver that can output idealy 800hz or below.
- 1 1 3/8" driver to 3/8" ID tube adapter that I designed, check the repo for the STL file
- 1 50 Watt amplifier board
- 1 1/4" TRS jack
- 1 Barrel Connector for power
- 1 2 amp 18 volt supply
- Hammond Enclosure, I used the 1456 slanted enclosure

# Schematic and Circuit Analysis
A detailed circuit analysis is avaliable at this [repo](https://github.com/codycarter1763/DIY-Distortion-Plus-Pedal), but I will attach the schematic I used here. 

With the 0.7 volt forward voltage of the silicon diodes, this leads to clearer and more aggressive distortion with more volume. I will attac the gerber files for the circuit board above
![Screenshot 2025-06-24 113447](https://github.com/user-attachments/assets/37b781fb-df23-4295-b3fe-a89203b49548)

# Closing
Hope you got someting out of this guide for building a talkbox pedal. I'll update this repository as I find new information or make any new upgrades.

