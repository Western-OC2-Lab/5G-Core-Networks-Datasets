# 5G-Core-Networks-Datasets

This repository contains the 5G Core Network datasets collected during packet capturing and observed in the following paper: 

<a href="https://arxiv.org/abs/2205.15121">Towards Supporting Intelligence in 5G/6G Core Networks: NWDAF Implementation and Initial Analysis</a>

Dataset1.pcapng captures initial UE registration with the 5G Core and 138 minutes of all other operations in the network. It can be opened using Wireshark or other packet dissection software. Dataset2.csv displays a selection of data fields per packet, including the following:

### No.
The sequence number of the packet during the collection phase.

### Time
The local emulation time appended to each packet when it was collected.

### Source
The source IP address, or the packet sender (see Network Topology section).

### Destination
The destination IP address, or the packet receiver (see Network Topology section).

### Protocol
The protocol of communication, or the communication scheme, that the packet is a part of.

### Length
The length of the packet, measured in bytes.

### Info
The information, or packet metadata, about the packet's transmission and any contained data.

## Network Topology

The source and destination IP addresses correspond to the following private network topology of the 5G Core:

192.168.0.10 -> MongoDB instance <br/>
192.168.0.11 -> NWDAF <br/>
192.168.0.12 -> NRF <br/>
192.168.0.13 -> AMF <br/>
192.168.0.14 -> SMF <br/>
192.168.0.15 -> AUSF <br/>
192.168.0.16 -> UDM <br/>
192.168.0.17 -> UDR <br/>
192.168.0.18 -> PCF <br/>
192.168.0.19 -> NSSF <br/>
192.168.0.20 -> BSF <br/>

192.168.0.21 -> UPF <br/>

192.168.0.22 -> gNB <br/>

192.168.0.23 -> UE  <br/>
