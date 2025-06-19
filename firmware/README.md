This folder contains source and include files, as well as the MCU setup .ioc file.
The software is a very short program that connects to MQTT and waits for a certain message. The server address, topic name, username, password and similar details are left with placeholders.
The software checks for a disconnection, and then restarts the connecting process.
There is no cybersecurity implemented in this version of the software.
The software is not fully optimized, so there are some *HAL_Delay()*'s scattered around.
