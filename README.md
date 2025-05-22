# Computer-Networks
# Network Microscope: Real-Time TCP/IP Analysis, Malware Detection & GeoIP Mapping using Wireshark

## Overview

*Network Microscope* is an advanced real-time network traffic analysis project that combines multiple functionalities into one integrated environment. It leverages *Wireshark, **GeoIP mapping, and custom rule sets to provide deep inspection of the **TCP/IP protocol stack*, decrypt test traffic, and identify malware behavior in network traffic.

This project is ideal for cybersecurity students, SOC analysts, and network engineers interested in understanding and visualizing the behavior of modern network communication, including attack detection and geographic traffic tracing.

---

## Features

- *Real-Time TCP/IP Protocol Analysis*: Live capture and breakdown of each OSI and TCP/IP model layer using Wireshark.
- *Decryption of Test Traffic*: Analysis and decryption of SSL/TLS or other encrypted protocols using known keys or captured handshakes.
- *Malware Traffic Detection*: Identification of malicious patterns using custom Wireshark filters and signatures.
- *GeoIP Location Mapping*: Maps IP addresses in real-time using MaxMind GeoLite2 and integrates with visualization tools.
- *Multi-layer Packet Dissection*: View and analyze data at application, transport, network, and data link layers.

---

## Technologies Used

- *Wireshark*
- *TShark (Wireshark CLI)*
- *MaxMind GeoLite2 DB*
- *Python* (for automation and GeoIP integration)
- *Scapy* (for custom traffic generation and analysis)
- *ELK Stack* or *Grafana + InfluxDB* (optional for visualization)
- *Malware PCAPs* (for detection validation)

---

## Project Structure

```bash
.
├── captures/                   # Sample PCAP files (normal and malicious)
├── scripts/                    # Python scripts for automation, GeoIP mapping
│   └── geoip_mapper.py
├── rules/                      # Custom filters and detection rules
├── reports/                    # PDF or Markdown analysis reports
├── visuals/                    # Screenshots and GeoIP maps
├── README.md                   # This file
└── requirements.txt            # Python dependencies
