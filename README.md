# Sub-Chapter-1.2-Interactive-UI-with-Push-Buttons.-
## More fun with Arduino
### This section demonstrates how to build interactive user interfaces with push buttons and an LCD using Arduino
### We'll learn how to code "Navigator buttons", "Counter button", "Parameter Tuner", etc.
## Features:
### Non-blocking LCD refresh
### Non-blocking push buttons debounce (Totally remove the dealy() function)
### Using the I2C interface to control the LCD
### Use of the control statement "switch(){}" 

## Learning notes: "switch" control statement:
### switch(){} is a control structure used to execute different blocks of code depending on the value of variable. It's essentially a cleaner alternative to writing multiple if...else statements when you need to handle several discrete cases. 
### Syntax:
#### switch(variable){
####   case value1:
####    // code of variable == value1
####    break;
####   case value2:
####    // code of variable == value2
####    break;
#### }

### Break statement (break;) prevents fall-through, without it, execution continue into the next case.

### This project is part of my Robotic and IoT learning journey with Arduino, supported by tools such as ChatGPT, Gemini, and Copilot. Simulations are run on Tinkercad and Wokwi.   
