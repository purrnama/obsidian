202308221622
Status: #idea
Tags: [[Data Link Layer]] [[Ethernet]]
# Frame
Packets are encapsulated in a frame that contains the necessary data for transmitting between devices. A frame consists of a header and a trailer.

### Header
- Frame start: indicating the start of a frame
- Addressing: Addresses of sending and receiving device
- Type:
- Control:

In between header and trailer is the data

### Trailer
- Error detection
- Frame stop

## Frame Size
Minimum: 64 bytes
Maximum: 1518 bytes

A frame larger than 1500 bytes is considered "jumbo" or "baby giant frames"


---
# References