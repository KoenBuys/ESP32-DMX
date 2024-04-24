# ESP32 DMX512

Example code for receiving and transmitting DMX512 with ESP32 and RS485 transceiver IC like MAX485 or isolated ADM2486.

Can be used with Arduino or plain ESP-IDF.

Driver inputs DMX using UART2 on GPIO pin 16.

Driver outputs DMX using UART2 on GPIO pin 17.

Driver uses pin 4 to change direction of dmx dataflow.

Even if it is an Arduino library, it is possible to use the two source files in IDF projects since it has no dependency on Arduino libraries.
