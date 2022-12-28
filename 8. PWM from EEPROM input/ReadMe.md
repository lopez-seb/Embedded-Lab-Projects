# PWM from EEPROM input

This lab controls the brightness of the onboard LED based on EEPROM input. 
Every time the board is booted, an incrementation is written to EEPROM. 
Once a certain amount is achieved it is reset. The value written to the incrementor is what is used to modulate the duty cycle of the PWM used for controlling the onboard LED. 
This lab can be observed here:
https://www.youtube.com/watch?v=O_LA_ujkAmg
