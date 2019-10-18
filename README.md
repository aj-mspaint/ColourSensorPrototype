# ColourSensorPrototype
A colour sensor created using an Arduino, a light-dependent resistor, and an RGB LED.

Our eyes recognise different colours from the frequency of the light reflected from the object. By recording the amount of light from different wavelengths that is either absorbed or reflected with an LDR, we can imitate this process.

You will need:
- 2x 220 ohms resistor
- m/m jumper wires
- Cathode RGB LED
- Light-dependent resistor
- Breadboard
- Arduino

Once your board is set up and programmed, you will have a five second window from when the program begins to place a white sample in front of the LED and sensor. Once the LED finishes flashing, you will have another five seconds to place the black sample. Once this is done, the balance has been calculated, and after five seconds the program will begin to read colours. You will be able to read the data being read from the serial monitor. Place objects in front of the sensor to try it out!
