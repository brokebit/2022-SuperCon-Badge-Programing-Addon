# 2022 SuperCon Badge USB Programing Add On Module
This project is an open-source hardware add-on that allows you to easily upload & download programs via USB and interact with the Input & Output pins via buttons and LEDs. It also passes all header pins through so you can daisy chain other add-ons. Input buttons, output LEDs, and USB UART can all be disabled via DIP switches. 

The board is a 6-layer design made in KiCad. The surface mount parts should be available directly from JLC PCB, and the through-hole parts are available via Digiki or your other favorite supplier. 

The 5V USB supply only powers the USB UART. 

## Through Hole Parts
- [12 Pin Femaile Header](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC121LGBN-RC/775906)
- [12 Pin Male Header](https://www.digikey.com/en/products/detail/adam-tech/PH1RA-12-UA/9830541)
- [4 Position SPST DIP Switch 2.54mm pitch](https://www.digikey.com/en/products/detail/grayhill-inc/76SB04T/726228)
- [2 Position SPST DIP Switch 2.54mm pitch](https://www.digikey.com/en/products/detail/grayhill-inc/76SB02ST/726171)
- [6mm Buttons](https://www.digikey.com/en/products/detail/te-connectivity-alcoswitch-switches/1825910-3/2400476)
## Features
- Passthrough header
- Four input buttons for input I/O pins
- Four output LEDs for output I/O pins
- CP210x USB Uart for serial I/O and upload/download programs
## Resources
- [Schematic](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/Schematic-111222-v0.1.pdf?raw=true)
- [BOM file for PCB Manufacturer](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/Manufacturing/BOM_ProgramingAddOn.xlsx?raw=true)
- [Position file for PCB Manufacturer](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/Manufacturing/ProgramingAddOn-pos.xlsx?raw=true)
- [Gerber files for PCB Manufacturer](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/Manufacturing/ProgramingAddOn.zip?raw=true)

![PCB Picture - Front](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/images/PCB-Rendering.png?raw=true) 
![PCB Picture - Back](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/images/PCB-Rendering-Back.png?raw=true)
![Picture, board plugged into badge](https://github.com/brokebit/2022-SuperCon-Badge-Programing-Addon/blob/main/images/IMG_0516.jpg?raw=true)

