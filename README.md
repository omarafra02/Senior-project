# UAV Secure Communication Simulation (Px4)

## Overview
This project simulates secure communication between a Ground Control Station (GCS) and UAV drones using Px4

## Features
- MAVLink protocol
- ChaCha20-Poly1305 encryption
- Anti-replay protection
- Replay attack simulation
- Retransmission

## Security Mechanism
- Each drone has a unique symmetric key
- Packets are encrypted using ChaCha20-Poly1305
- Replay protection implemented using sliding window
- Duplicate and replayed packets are detected and blocked
- Packets lost in network will be retransmited
## Report
The full project report (including results and screenshots) will be added to this repository after the project is finished
## Note
- this read.me is not finished it will be updated later
