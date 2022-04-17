# Serial-Peripheral-Interface

A microcontroller can send multiple bits to a peripheral device by using multiple wires or by sending multiple bits in series over a single wire. The former is called 
parallel I/O and the latter is called serial I/O. Serial I/O is popular, especially when pins are limited, because it uses few wires and is fast enough for many 
applications. Indeed, it is so popular that many standards for serial I/O have been established and microcontrollers offer dedicated hardware to easily send data via
these standards. This repository describes the salient features of SPI standard and its implementation in SystemVerilog.

SPI (pronounced “S-P-I”) is a simple synchronous serial protocol that is easy to use and relatively fast. The physical interface consists of three pins: serial clock 
(SCK), serial data out (SDO), and serial data in (SDI). SPI connects a controller device to a peripheral device, as shown below:

<p align="center">
  <img width="50" height="50" src="https://user-images.githubusercontent.com/61377755/163710225-fc190afe-36a1-43aa-8ac1-652bb2cfdbb3.png">
</p>



