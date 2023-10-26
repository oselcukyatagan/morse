# morse
The documantation for the Morse Code Interpreter project.

Problem Statement and Objectives:
    Morse code is crucial to know in emergency situations where a person can not be heard or is not in a position to speak. However, learning morse code can be a difficult process. The project’s goal is making Morse code communication possible for everyone, regardless of their familiarity with the code. The final product will be a device that converts English input into Morse code, displaying it through an LED, LCD, and buzzer.



Background Information:
    Today, morse code translators can be found online. While online Morse code translators make Morse code communication more accessible, they can not be used when there is no internet connection. In many emergency situations, an internet connection is not possible. 

   In an emergency situation where someone is stuck somewhere underground, people can not use their voice after a long time. By hitting something that can produce loud noises, people can communicate via Morse code when they can not use their voice. This project can benefit society by making Morse code communication accessible to everyone.

Some online Morse code translators: 
•	https://morsedecoder.com/
•	https://morsecodes.io/
•	https://morsecode.world/international/translator.html

Project design
   Project design consists of a Bluetooth connection and 3 output devices, namely LCD led and buzzer. Bluetooth Module takes the data and passes it to the Arduino. Arduino decides which letter to display and that letter then gets printed as Morse code in LCD, LED and buzzer.


Project components:
  Arduino Uno
  HC-06 Bluetooth Module
  LCD 
  DS3231 Clock Module
  Breadboard
  Push button
  LED
  Buzzer
  Potentiometer
  Jumper cables


Circuit diagram:

![image](https://github.com/oselcukyatagan/morse/assets/115888665/fa74516b-85f0-4894-888d-a16af81f79cb)

* Rectangle in the down-right represents bluetooth module, from left to right the pins are 
RXD, TXD, VCC, GND  


A photo of the project:

![image](https://github.com/oselcukyatagan/morse/assets/115888665/d2fa8d39-16ea-470c-886c-2927918a51f2)

  The project can succesfully turn English input into morse code and display it through output devices. Due to the size of the LCD, morse code displays get erased after each letter, to make room for the next letter. With a bigger screen, LCD can display a word before it gets erased for the next word to display.

Possible improvements:
  This project can be improved algorithm-wise by mapping English letters to Morse code letters. The buzzer can be changed with a louder buzzer. A cover for the project can be designed to make it more aesthetically pleasing.

I learned: 
•	bluetooth communication with arduino,
•	how to use an LCD with an arduino,
•	how to use a real time clock,
•	external interrupts (push-button was going to be an external interrupt, however digitalRead is easier to use and understand). 

