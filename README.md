# Playable-Environment
Open Source library to connect an Arduino microcontroller to Unity 3D via serial.
It is under construction so you can find some bugs.

# Install Library

## Arduino Sketch
You will find in firm\Console\ path the Arduino source code. It must be compiled first and written on Arduino. There is only support
in Arduino MEGA 2560, but in a near future will be able to other microcontrollers Arduino-based.

## Unity 3D
The Assets\Scripts path contains the Arduino library classes. Remember, this proyect is still being developed,
it will be more changes soon.

### Classes Structure
* "ArduinoBaseController" contains the basic code to connect via serial the microcontroller.
* "ArduinoController" extends from "ArduinoBaseController" and its structure is Arduino-like structure (this is the file that you must add to your GameObject, it may be your main character).
* "AboutUI" contains an example to comunicate between Unity UI System and Arduino ports.

# Extra Info
* Windows support only.
* Our code runs under 9600 baud rate. If you need to change that value you must change it on Unity Editor Script (ArduinoController class) and "SERIAL_BAUDRATE" on Arduino Sketch (recompile it).
* In some cases you will get many compilation errors. Only try to change the variable "Api Compatibility Level" to ".NET 2.0" from "Player Settings".

# About Us
We are an organization located on Guadalajara Jalisco, MX that develops educational software. For more info visit us in our [official site](https://www.besoft.com.mx/)
