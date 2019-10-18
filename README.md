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

Once your board is built and programmed, you will have a five second window from when the program begins to place a white sample in front of the LED and sensor. Once the LED finishes flashing, you will have another five seconds to place the black sample. Once this is done, the balance has been calculated, and after five seconds the program will begin to read colours. You will be able to read the data being read from the serial monitor. Place objects in front of the sensor to try it out!

fjordcarver did an excellent tutorial of a similiar project, for further reading, see it on instructables.com: https://www.instructables.com/id/Using-an-RGB-LED-to-Detect-Colours/
or Techmartin's tutorial, also on instructables:
https://www.instructables.com/id/How-to-Use-RGB-LEDs-to-Identify-Colours-DIY-Colour/

For further investigation of basic colour sensors, see this tutorial on LEDs by WolfxPac on Arduino Project Hub:
https://create.arduino.cc/projecthub/WolfxPac/led-as-a-light-sensor-aea288
Or lady ada's photocell tutorial published on adafruit:
https://learn.adafruit.com/photocells/using-a-photocellon
