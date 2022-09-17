# arduino-LCD
Arduino UNO and LCD interfacing without potentiometer + Arduino code
## Hardware required
1. Arduino UNO
2. 16x2 Alphanumeric LCD
3. Jumper cables
## Software required
Arduino IDE
## About this project
In this project we will only be using a LCD, Arduino uno, jumper wires to display text on the LCD. We will use the digital pin 6 to control the contrast value of the LCD. The function to display text on the lcd will be | lcd.print (“Your text here”) .
## Procedure
### Step 1: HW set up
Connect the pins from the LCD (left) to the Arduino UNO (right) [directly without breadboard], according to the pins indicated in the following text.
1. Vss  -> GND
2. Vdd  -> 5V
3. Vo   -> Digital pin 6
4. Rs   -> Digital pin 12
5. Rw   -> GND
6. E    -> Digital pin 11
7 - 10: no connections
11. D4  -> Digital pin 5
12. D5  -> Digital pin 4
13. D6  -> Digital pin 3
14. D7  -> Digital pin 2
15. A   -> 5V
16. K   -> GND
### Step 2: Code
1. Refer the "lcd-code.ino" file
2. Code it in Arduino IDE
3. Connect the Arduino UNO to your computer
4. From the tools menu select the port and board correctly
5. Hit the upload button and the text shall be displayed on your LCD.

ENJOY!
