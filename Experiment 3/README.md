# Experiment 3: Packet Switching vs Circuit Switching

## Aim

To create a network simulation to demonstrate packet switching and circuit switching and compare their performance and efficiency.

## Objective

To understand the difference between packet switching and circuit switching by simulating data transmission in both methods.

## Theory

Packet switching is a method of data transmission in which data is broken into small packets and each packet can take different paths to reach the destination. It is efficient and flexible.

Circuit switching is a method in which a dedicated communication path is established between sender and receiver before transmission begins. All data follows the same path.

## Network Topology

### Packet Switching


### Circuit Switching
![Circuit Topology](screenshots/circuit_topology.png)

## Procedure

1. Open Cisco Packet Tracer
2. Create a network with multiple routers and PCs
3. Design two paths between source and destination for packet switching
4. Send data using simulation mode and observe packet flow
5. Modify the network to create a single fixed path for circuit switching
6. Send data again and observe behavior

## Configuration Commands

Basic IP configuration was done on PCs and routers.
No advanced routing protocols were used.

## Observations / Results

### Packet Switching

* Packets followed different possible paths
* Dynamic routing observed
* Better fault tolerance

![Packet Flow](screenshots/packet_flow.png)

### Circuit Switching

* Data followed a single fixed path
* No alternate route available
* Less flexible compared to packet switching



## Conclusion

The experiment successfully demonstrated both packet switching and circuit switching. Packet switching proved to be more efficient and flexible as it allows multiple paths and better utilization of network resources, whereas circuit switching follows a fixed path and is less efficient.

