
# Assignment 2: Packet Switching vs Circuit Switching

## Aim

To simulate packet switching and circuit switching and compare their performance.

## Objective

To understand how data transmission differs in packet switching and circuit switching.

## Theory

Packet Switching:
Data is divided into small packets and each packet can take different paths to reach the destination. It is efficient and flexible.

Circuit Switching:
A dedicated path is established before data transmission. All data follows the same path. It is less flexible but reliable.

## Network Topology

### Packet Switching

![Packet](screenshots/packet_topology.png)

### Circuit Switching

![Circuit](screenshots/circuit_topology.png)

## Procedure

1. Open Cisco Packet Tracer
2. Create network with multiple paths for packet switching
3. Send packets using simulation mode
4. Modify network to create single path for circuit switching
5. Send packets again and observe behavior

## Configuration

IP addresses assigned manually.
Static routing used for connectivity.

## Observations / Results

### Packet Switching

* Packets followed different paths
* Efficient use of network
* Better fault tolerance

![Packet Flow](screenshots/packet_flow.png)

### Circuit Switching

* Fixed path used
* No alternate route
* Less efficient

![Circuit Flow](screenshots/circuit_flow.png)

## Conclusion

Packet switching is more efficient and flexible compared to circuit switching, while circuit switching provides a dedicated path but lacks adaptability.
