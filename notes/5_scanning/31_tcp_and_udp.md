# TCP and UDP
- Protocols used for sending bits of data/packets over the internet

## TCP: Transmission Control Protocol
- Most commonly used protocol on the internet
- TCP is the reliable protocol and makes sure all the packets reach destination without any errors
- TCP Three Way Handshake
  - syn : synchronize sequence number
    - Client to server
    - Informs server that client wants to start communication and what # to start sequence with
  - syn/ack
    - Server back to client
    - Agress upon the sequence number and acknowledges
  - ack : acknowledges response
    - Client acknowledges response of server and establishes connection

# UDP: User Datagram Protocol
- Works similarly to TCP but doesn't use any of the error checking
- Useful when speed is desired and accuracy isn't really a concern (live streams, gaming, etc.)
  - Doesn't need to resend packet if it doesn't reach the other end (cant resend it anyway)
- Fire and forget (no handshake)
