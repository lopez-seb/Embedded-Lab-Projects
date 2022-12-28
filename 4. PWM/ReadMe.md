# PWM using LED and onboard switch

The brightness of the on board LED is contolled based on how long the onboard switch is held.
This is done using a hardware ISR timer set to a 10ms period where the duty cycle is increased as long as the button is held down. When the button is released, the duty cycle ramps down in a similar manner until it reaches zero.
A demonstration of this code can be seen here:
https://www.youtube.com/shorts/k5QS8mubxG4
