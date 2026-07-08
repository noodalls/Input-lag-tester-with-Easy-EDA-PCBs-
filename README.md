This is what I've been working towards. 

Included are 10 files. 

In order to order a PCB, three files are required. 

The GBR files defines the physical shape of the board. The BOM file dictates the parts used and the Pick and Place file dictates where those parts are placed on the PCB.

There are three sets of files

The PT board is the simplest. This has a phototransistor and a audio cable socket. 

The Main baord is where most of the activity happens. This requires

- a PICO2W board to be programmed and plugged in.
  - There is text on the board to ensure that the orientation is correct.

- You would also benefit from having an OLED screen.
  - The boards I use is 0.96 Inch OLED 12864 128x64 SSD1306 Driver I2C Serial Display.
  - Please note, the pin order must be GND VCC SCL SDA.
  - I have found some boards with GND and VCC flipped. This doesn't end well.
 
- You can also plug in a 3 colour LED.
  - The board I use is described as 3 Colour RGB LED Module for Arduino on ebay
  - This should have a GND pin. If the 3 colour RGB has a + or VCC or 3V3 or 5V pin it at best won't work.
 
- You need one auxillary cable for each PT board.

- I'll look to upload a youtube video to explain how to set it all up
