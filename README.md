# UDP Pinger

Simple client & server network applications for calculating the RTT (Round Trip
Time).

### Application flow

Flow 1
* The client sends a ping message to the server.
* The server receives the ping message.
* The server responds with a pong message to the client.
* The client receives the pong message.
* The client prints the RTT (Round Trip Time).

Flow 2
* The client sends a ping message to the server.
* The ping UDP packet gets lost.
* The client waits 5 seconds for a response.
* The client prints that the packet got lost.
