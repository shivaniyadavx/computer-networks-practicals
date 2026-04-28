
# Experiment 1: Star Topology

## Aim

To design and implement a star topology using Cisco Packet Tracer.

## Objective

To understand how devices communicate in a star topology network and to verify connectivity between them.

## Theory

Star topology is a network configuration in which all devices are connected to a central device such as a switch. Each device has a dedicated connection to the central device. It is easy to install, manage, and troubleshoot. However, if the central device fails, the entire network goes down.

## Network Topology

![Topology](screenshots/topology.png)

## Procedure

1. Open Cisco Packet Tracer
2. Add one switch and multiple PCs
3. Connect all PCs to the switch using copper straight-through cables
4. Assign IP addresses to each PC
5. Verify connectivity using ping command or simulation mode

## Configuration Commands

No router or switch configuration commands were required.
IP addresses were assigned manually on each PC.

PC0: 192.168.1.1
PC1: 192.168.1.2
PC2: 192.168.1.3

Subnet Mask: 255.255.255.0

## Observations / Results

Successful communication was observed between all PCs.
Ping test was successful and packets were transmitted correctly in simulation mode.

![Ping Result](screenshots/ping_success.png)

## Conclusion

The star topology was successfully implemented using Cisco Packet Tracer. All devices were able to communicate with each other, verifying correct network configuration.
