# bus1_MPR121
modified MPR121 library for Arduino that allows you to define which i2c bus you are using

I am using this on a teensy 4 - remember that you will need to pull up SDA1 and SCL 1 to 3.3v using a 2.2k resistor if you want to use them. 

This gets rid of weird and unpredictable behaviour when combining the Teensy Audio Shield with MPR121 sensors. 
