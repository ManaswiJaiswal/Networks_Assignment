# Error Detection using Cyclic Redundancy Code (Using CRC-8)
## Overview
This project implements a Stop-and-Wait based data link layer level logical channel between two nodes: A (client) and B (server), using a socket API. It simulates communication over a network with error detection using Cyclic Redundancy Code (CRC-8). The protocol includes mechanisms for message acknowledgment (ACK) and negative acknowledgment (NACK), as well as a concurrent server design capable of handling multiple clients simultaneously.

## Features
- *Error Detection:* Utilizes CRC-8 for error checking in messages.
- *ACK/NACK Mechanism:* Implements acknowledgment and negative acknowledgment for message integrity.
- *Concurrent Server:* Capable of serving multiple clients at the same time.

## Compilation
To compile the client and server programs, follow these steps:

1. Open a terminal.
2. Navigate to the project directory.
3. Run the make command:

bash
make



## Running the Server

After successful compilation, you can start the server by executing the following command in the terminal:

bash
./server <Server Port Number>



## Running the Client

To run the client, open a new terminal window and execute:

bash
./client <Server IP Address> <Server Port Number>
