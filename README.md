# drone-stm32

## How to get started with STM32 blue-pill?
1. Follow this good tutorial: 
- [YouTube](https://www.youtube.com/watch?v=Myon8H111PQ)
- [Electronics Hub](https://www.electronicshub.org/getting-started-with-stm32f103c8t6-blue-pill/)

### Notes
Tools: Program using FTDI cable

Pin Assignment
Gnd --> Gnd
Vcc --> Vcc
TXD --> A10
RXD --> A9

### Steps
1. Install the board package
2. Install STM32 CubeProgrammer
3. Download STM32 HID Bootloader 2.2.1 (in case you want to use the native USB cable, need to also modify the resistant)

### Other Tutorials
- STM32 BLUEPILL USB BOOTLOADER SUPPORT [HERE](https://www.youtube.com/watch?v=fD1Bzf2iP_E)
- How to install STM32 CubeProgrammer for Mac [HERE](https://stackoverflow.com/questions/67534444/installing-stm32cubeprogrammer-on-macos-big-sur) 

## Navigation
- Program STM32 [HERE](https://www.sgbotic.com/index.php?dispatch=pages.view&page_id=48)
- Drone STM32 [HERE](http://www.brokking.net/ymfc-32_main.html)

## DIY STM32 Drone Development Steps
- [ ] Harware procurements
  - [x] Frame
  - [x] Stm32 board
  - [x] Motor + ESC
  - [ ] IMU MPU-6050
  - [ ] LED
  - [ ] PCB protoboard
  - [ ] Resistor
  - [ ] Battery
  - [ ] Battery connector
  - [ ] Battery charger
  - [ ] RC transmitter and receiver
- [ ] (SW) Basic of STM32
  - [ ] Getting started with STM32 (blink)
  - [ ] STM32 + MPU-6050
  - [ ] STM32 + RC Receiver
  - [ ] STM32 + ESC
  - [ ] Breadboard (long)
  - [ ] Some wires
- [ ] PCB drawing 
- [ ] (Assem) PCB board design & build
- [ ] (Test) manual flight test
- [ ] Prop Jig Build