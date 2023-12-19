This Repo is about the Gesture Controlled Arduino device 👋.


Components we require 🪛:

✔️ Ultrasonic sensors (2 NOS)

✔️ Arduino UNO Boards


Now We have Two modes in arduino, 

1️⃣ The first one in programming mode 

2️⃣ The second one is Keyboard mode


To have the Arduino in any mode we require the respective firmware. 

They are placed in the 📁 HEX folder in the Repo.


How to change Arduino's Firmware❓

✔️ You need a shorting wire (wire with two Female points)

✔️ Then your Arduino should be connected to a power source (i.e. Laptop/PC) 💻

✔️ Atmel FLIP software (Installer is present in the Repo)



1️⃣ Now Short the Arduino Board So that it gets into DFU (Device Firmware Upgrade mode)

2️⃣ Then Open your Atmel FLIP software and choose your Arduino Port and select the firmware you wanted to upgrade to.

3️⃣ Done!


 Watch this video if you have any trouble doing 📹 --> https://www.youtube.com/watch?v=fSXZMVdO5Sg&t=349s

 

 You have ino code in the keysyscontrol folder 📁.
 
⚠️ You can burn code into the Arduino board only in the *Arduino-usbserial-uno.hex* firmware

⚠️ And you can only execute the code in the *Arduino-keyboard-0.3.hex* firmware



So be careful while handling the Board.


Now Burn the Code in the keysyscontrol folder 📁 and run the Board in the respective firmware while using it.


You can customize the keyboard keys in the ino code for the arduino.


**You can only use the above code for softwares which support custom key binding i.e. VLC media player**
