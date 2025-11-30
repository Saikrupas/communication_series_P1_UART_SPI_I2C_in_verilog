## 🔌  UART,SPI,I2C serial protocols 
+ <u>UART, SPI, and I2C are all serial communication protocols</u> for embedded systems, but they differ in speed, complexity, and wiring.
+ UART is a simple, asynchronous, full-duplex protocol for point-to-point communication over two wires, often used for longer distances.
+ SPI is a faster, synchronous, full-duplex protocol that uses four wires (or more for multiple slaves) in a single-master, multi-slave setup.
+ I2C is a synchronous, half-duplex protocol using two wires for multiple masters and slaves on a short-distance bus, with speeds typically slower than SPI but faster than UART.

### 🔧 Features

**🎯 SPI(Serial Peripheral Interface) protocol**
+ Communication type: Synchronous, serial, full-duplex
+ Wiring: Four wires (MOSI, MISO, SCK, SS)
+ Complexity: Moderate to high, especially with many slaves
+ Speed: Fastest of the three (can reach tens of Mbit/s)
+ Addressing: Uses a Slave Select (SS) line for each slave
+ Best for: High-speed data transfers, such as with memory chips or high-resolution displays

**🎯 UART(Universal Asynchronous Receiver/Transmitter) protocol**
+ Communication type: Asynchronous, serial, full-duplex
+ Wiring: Two wires (Tx and Rx)
+ Complexity: Simple
+ Speed: Slowest of the three (e.g., up to 115,200 bps)
+ Addressing: No inherent addressing; point-to-point only
+ Best for: Simple, one-to-one communication, long-distance communication, and debugging

**🎯I2C (Inter-Integrated Circuit) protocol**
+ Communication type: Synchronous, serial, half-duplex
+ Wiring: Two wires (SDA and SCL)
+ Complexity: Moderate
+ Speed: Moderate (up to 3.4 Mbps or higher in some modes)
Addressing: 7 or 10-bit addressing scheme to support multiple devices on the same bus
Best for: Short-distance communication with multiple sensors, microcontrollers, and other peripherals on a single bus   
