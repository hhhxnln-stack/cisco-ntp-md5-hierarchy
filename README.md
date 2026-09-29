# cisco-ntp-md5-hierarchy
Multi-tier Cisco NTP hierarchy with MD5 authentication built in Packet Tracer.
# Multi-Tier Cisco NTP Hierarchy with MD5 Authentication

![Cisco](https://img.shields.io/badge/Cisco-IOS-blue?logo=cisco)
![Packet Tracer](https://img.shields.io/badge/Packet--Tracer-v8.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

# Project Overview
This project demonstrates the design, deployment, and verification of a secure, multi-tier Network Time Protocol (NTP) infrastructure across a routed Cisco network. It features an authoritative NTP Master (Stratum 1), transit NTP client/server propagation, and MD5 authentication keys to ensure tamper-proof timestamping across all devices.

# Network Topology

[R1(NTP Master)] <- 200.1.1.0/30 -> [R2 (Stratum 2)] <-10.0.0.0/30 -> [R3 (Stratum 3)]