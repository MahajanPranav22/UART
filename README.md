UART Verilog Description

**UART** (Universal Asynchronous Receiver/Transmitter) is a serial communication module that enables data transfer between digital systems without a shared clock. 
The design typically consists of a UART Transmitter (TX) and UART Receiver (RX).

**Transmitter**: Converts parallel 8-bit data into a serial bit stream with start bit, data bits, optional parity, and stop bit.

**Receiver**: Samples the incoming serial data, detects the start bit, reconstructs the 8-bit data, and generates a data-valid signal.

**Baud-rate generator**: Produces the required timing for serial transmission/reception.

**FSM-based control**: Controls the TX/RX sequence and ensures correct timing and data sampling.

