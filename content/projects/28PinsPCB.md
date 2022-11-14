---
date: '2020-01-01'
title: '28 Pins Arduino Board PCB'
github: 'https://github.com/theRaihann/28-Pins-Arduino-Board-PCB-using-Altium'
external: ''
tech:
  - Altium
company: 'BUET'
showInProjects: true
---
There are two microcontrollers placed on the board, ATMEGA328P and ATMEGA16U2.
Both RESET pins ( 16U2 and 328P ) are driven through an open drain buffer. This means: improved RESET quality and it adds an option to debug the microcontrollers through dWire.
ATMEGA16U2 can now be used as an universal AVRISP MKII programmer. Once you change the firmware, you can use it to program the onboard ATMEGA328P or any other board.




