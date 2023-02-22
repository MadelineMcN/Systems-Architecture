# Projects included:

### Timer Interrupt lab (Milestone 3):
In this lab, I used the TI Code Composer Studio (CCS) to program the TI CC3220x LAUNCHXL to send a Morse code message via the LED using a synchronous state machine.  The objective was to blink the green, yellow, and red LEDs in the lower right corner of the board. To do this, I designed a synchronous state machine that creates a pattern of blinking lights from the LEDs. This pattern contained a message in Morse code. When a button is pressed, the Morse code message of the blinking LEDs changed.


### Thermostat Lab (Final Project)
In this project, I used CCS to program the TI CC3220x LAUNCHXL to function as a low-level thermostat. The TMP006 temperature sensor reads the room temperature (via I2C), an LED indicates the output to the thermostat where LED on = heat on (via GPIO), the two buttons increase and decrease the set temperature (via GPIO interrupt), and the UART simulates the data being sent to the server.

## What did you do particularly well?
One thing I did well in these projects is implementing switch cases in both that dictate what action the program takes at any given time while running.

##  Where could you improve?
One thing I think I can improve on with these projects is implement more algorithmic design to make the codebase more reusable, less clunky, and easier to maintain. 

##  What tools and/or resources are you adding to your support network?
I look forward to including embedded C on my resume as I look forward to continue learning about embedded systems and creating projects around them. The user manual for the microcontroller ended up being my main resource for these projects.

##   What skills from this project will be particularly transferable to other projects and/or course work?

One thing that is transferable from these projects to other projects and course is the concepts of timers and interrupts. Even without a physical device involved, software often adheres to a timer for certain actions. For example, a timer that dictates when a user has to re-login in after being idle or a streaming services asking a user if they are still watching after so many episodes. Like the concept if a timer, interrupt is a concept that can be seen in almost every software, where a program will behave one way until some external action happens and prompts the behavior of the program to change. 

##  How did you make this project maintainable, readable, and adaptable?

Documentation is one of the best ways to ensure a project is readable. Cohesive and consistent variable naming is also helpful with readability. Maintainability can be ensured by writing code that is testability and testing often. One way to make sure code is adaptable is modularizing code when it makes sense.
