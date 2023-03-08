# Projects included:

### Timer Interrupt lab
In this lab, I used the TI Code Composer Studio (CCS) to program the TI CC3220x LAUNCHXL to send a Morse code message via the LED using a synchronous state machine.  The objective was to blink the green, yellow, and red LEDs in the lower right corner of the board. To do this, I designed a synchronous state machine that creates a pattern of blinking lights from the LEDs. This pattern contained a message in Morse code. When a button is pressed, the Morse code message of the blinking LEDs changed.


#Thermostat lab
In this project, I used CCS to program the TI CC3220x LAUNCHXL to function as a low-level thermostat. The TMP006 temperature sensor reads the room temperature (via I2C), an LED indicates the output to the thermostat where LED on = heat on (via GPIO), the two buttons increase and decrease the set temperature (via GPIO interrupt), and the UART simulates the data being sent to the server.

