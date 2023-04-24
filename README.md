# MICROCONTROLLER_TRAFFIC-LIGHTS_ASSIGNMENT

There are 2 files: a coding file (main.zip) and a .txt file containing the link to a demonstrating video.

1. The project needs to run on STM32CubeIDE platform (C language).

2. Sending commands and interacting with the board using UART.

3. Project materials:
  + Simulating a crossroads traffic lights system.
  + Connecting the board to the computer through USB port.
  + Using STM32 ST-LINK Utility to read the code and transmit the code (.hex file) from the computer to the board.
  + Using Hercules to send UART commands to the board.
  
4. Project description:
  + After successfully connected, send '0' to the board and wait 5 seconds to run the system in NORMAL mode.
  + If users want to change the Green lights time, send '2' to the board and send any number users want the Green lights to run.
  + If users want to change the Yellow lights time, send '3' to the board and send any number users want the Yellow lights to run.
  + After successfully adjusted, press 0 again to run the system with updated time.
