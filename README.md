# LED Blink Project
## Project Overview
This project demonstrates a simple LED blinking circuit using an Arduino Uno. The LED is connected through a resistor and programmed to blink continuously.
## Components Used
- Arduino Uno
- LED
- 220Ω Resistor
- Connecting Wires
## KiCad Files
 LED Blink.kicad_sch
 LED Blink.kicad_pcb
 LED Blink.kicad_pro
## Arduino Code
void setup() {
  pinMode(13, OUTPUT);
}
void loop() {
  digitalWrite(13, HIGH);
  delay(200);
  digitalWrite(13, LOW);
  delay(200);
}
## Wokwi Simulation
Wokwi Project Link:
https://wokwi.com/projects/465416115946933249
## Author
Gayathri Inaganti

