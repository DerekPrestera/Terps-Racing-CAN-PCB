# Terps-Racing-CAN-PCB
A custom Arduino Uno Shield to construct a CAN network data collection system

This board is the basis for a CAN network based sensor system for Terps Racing vehicles. It is a shield for Arduino uno that allows the Arduino to communicated on a CAN netowrk with the MCP2515 CAN to SPI chip and read analog sensor data with 12-bit resolution with the MCP3208 ADC chip. This turns the Arduino into a data collection CAN Node that can be placed right next to the location of a sensor and transmit its reading to the vehicle's CAN bus for logging, telemetry, or possibly use by data-driven active components elsewhere on the vehicle. 

![Picture of the PCB](https://github.com/DerekPrestera/TerpsRacingProjects/blob/main/CAN-Shield/pcb-pic.png)