# 5G-Core-Networks-Datasets

This repository contains the 5G Core Network datasets collected during packet capturing. Dataset1.pcapng captures initial UE registration with the 5G Core and 138 minutes of all other operations in the network. It can be opened using Wireshark or other packet dissection software.

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
