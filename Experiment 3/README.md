# Assignment 3: Network Performance Analysis

## Aim

To analyze packet delay, packet loss, and throughput in a network.

## Objective

To understand how network performance is affected by routing and traffic conditions.

## Theory

* Packet Delay: Time taken for data to travel from source to destination
* Packet Loss: Loss of packets during transmission
* Throughput: Amount of data successfully transmitted

Routing algorithms affect these parameters.

## Network Topology

![Topology](screenshots/topology.png)

## Procedure

1. Open Cisco Packet Tracer
2. Create network with routers and PCs
3. Assign IP addresses
4. Configure routing (static/dynamic)
5. Send packets using simulation
6. Observe delay and packet movement

## Configuration Commands

Basic router configuration:

enable
configure terminal
interface fa0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

## Observations / Results

* Delay observed in packet transmission
* No packet loss under normal conditions
* Throughput improved with proper routing

![Result](screenshots/simulation.png)

## Conclusion

Network performance depends on routing and traffic. Efficient routing improves throughput and reduces delay.


