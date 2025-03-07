# DecibelProject
Decibel Project Grove Kit V3

Requirements (6):
· Computer (to simulate code)
· Arduino Yun
· Microphone Sensor Module (Grove kit)
· Cables (Grove kit)
· LCD Display (Grove kit)
· Sound Source

Equipment:
Component	Description	Amount
Arduino Board	Uno/Nano/MEGA	1
Microphone Sensor Module	Analog sound sensor module	1
RGB LCD Display	LCD Display with RGB backlight	1
Breadboard	Standard prototyping board	1
USB Cable	For power and programming	1



Required Libraries:
These are the required libraries in the Arduino IDE:
Wire.h
rgb_lcd.h

To install:
1.	Open Arduino IDE
2.	Go to Sketch ~ Include Library ~ Manage Libraries
3.	Search for rgb_lcd and click install.

Initial Setup:
1.	Connected to the Arduino.
2.	Uploaded our Arduino code.
3.	Observed LCD behaviors under different sound levels.
   
Expected Behavior:
Decibel Range	Expected Message	Expected Colour
0 - 60	Fair Sound	Green
61 - 85	Loud Sound	Yellow
86+	Dangerous	Red

