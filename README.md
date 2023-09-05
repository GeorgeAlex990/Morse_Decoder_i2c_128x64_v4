# Morse Decoder v4
Simple morse decoder with arduino that have full range alphabet and numbers. 
It can decode one letter/number at the time.


Morse decoder V4
By YO2GAR
 
Decodes one letter/number at the time
Has full range of alphabet and numbers
 
A dot is equal to every impulse that is larger than 50 millis(0.05 sec) and smaller than 150 millis(0.15 sec)
A line is equal to every impulse that is larger than 150 millis(0.15 sec)

Use Display library: https://github.com/GeorgeAlex990/LCD.h

My hardware:
  - Arduino Nano with CH340 USB 
  - A 5V active buzzer
  - A LED
  - One 330R resistor
  - A push button
  - A breadboard that can fit the Arduino Nano, a push button and a Buzzer
  - An Oled display
  - Jump Wires

Connections:
| Arduino Nano | Display |
|--------------|---------|
| 5V           | VCC     |
| GND          | GND     |
| SDA          | SDA     |
| SCL          | SCL     |
 
| Component   | Arduino Nano |
|-------------|--------------|
| LED         | Pin 9        |
| Buzzer      | Pin 9        |
| Push Button | Pin 2        |
