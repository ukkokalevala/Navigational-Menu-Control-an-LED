Short Description: LED Control Project
What It Does
A menu system on OLED display that controls an LED (GPIO 2) with 3 modes using a rotary encoder.

Hardware (5 components)
Component	Pins Used
ESP32-C3	Main board
OLED Display	SDA=9, SCL=8
Rotary Encoder	CLK=4, DT=5, SW=6
LED + Resistor	GPIO 2 (+), GND (-)
Menu Options
LED OFF - LED turns off

LED ON - LED stays lit

LED BLINK - LED flashes every 0.5 seconds

How to Use
Turn encoder → Navigate menu

Press encoder → Apply selected mode

LED responds immediately

Status
WORKING - All 3 LED modes functional, clean menu display.

What It Does (One Sentence)
Turns a rotary encoder into a menu controller that lets you select between turning an LED OFF, ON, or BLINKING, with real-time feedback on an OLED display.
