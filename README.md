# Mars_Task_2
In this code we have used the md10c motor driver to make a two wheel drive.
Here, Two motors and two motor driver boards are used.
Pins named pwm1 and pwm2 are connected to the pins 9 and 10 respectively and are responsible for changing speed of the motor.
pins named rightfor and leftfor are responsible for direction of the motor.
Both motors are powered by a 12V battery.
Initial idea was that the user should give input as W,A,S or D in the serial monitor which will be stored in a string variable named 'input'.

1.If this input is W then the code for moving the vehicle forward will run,

2.If this input is A then the code for moving the vehicle left will run,

3.If this input is S then the code for moving the vehicle backward will run,

4.If this input is D then the code for moving the vehicle right will run

However, there was some issue in the code. We tried using single quotes as well as double while checking for condition in the code (for example- if(input=="A") as well as if(input=='A')) but both did not work. Initially one pin was connected wrong which was later fixed.
