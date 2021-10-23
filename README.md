# Door_Locker_Security_System



[![Build Status](https://img.shields.io/badge/Embedded&nbsp;C-100%25-green)](https://travis-ci.org/joemccann/dillinger) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Build Status](https://img.shields.io/badge/commit%20activity-1weeks-blue)](https://travis-ci.org/joemccann/dillinger) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<br />

• Door Locker Security System consists of two ECU’s. The first ECU called HMI responsible for interfacing with the user and the second ECU called control ECU which is responsible for the system operations and control.<br />
• Implemented the following drivers Keypad, LCD, DC Motor, UART, Timer, I2C and External EEPROM.

1- The system asks the user to enter a password and verify the password entered.<br />
2- The next phase the system asks the user if he wants to open the door or change the password.<br />
3- If the user chooses to change password then he is capable of changing the password and then is redirected to phase 2.<br />
4- If the user chooses to open the door, he has 3 chances to enter the password correctly.<br />
-If the password is entered correctly within the 3 chances the door will open in 30 seconds and then stay opened for an extra 3 seconds and then close again in 30 seconds.<br />
-Else the buzzer is activated and the whole system is locked for 60 seconds.


## Components Used

- 2 * 8-bit AVR Microcontroller with 16K Bytes In-System Programmable Flash
- LCD
- DC MOTOR
- L293D (Dual DC Motor Controller)
- Keypad
- Buzzer




## Languages Used

- Embedded C


## Softwares Used

- Eclipse
- proteus

<p align="center">
  <img alt="gif" src="https://github.com/YasserAhmedMoh/Door_Locker_Security_System/blob/main/DoorLockerSecuritySystem.png" />
<p>
