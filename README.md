GitHub Repository Details

    Repository Name: Network-Traffic-Analyzer-IDS

    Short Description:

        "A network monitoring and security tool developed with Python and Scapy, featuring real-time packet analysis, SYN Scan anomaly detection, and GeoIP integration."

README.md Content

Bu metni kopyalayıp deponun ana sayfasına ekleyebilirsin:
Network Traffic Analyzer & IDS 🛡️

This advanced network analysis tool is designed for real-time traffic monitoring and intrusion detection. Developed as a security project during my 3rd year in Computer Engineering, it combines packet inspection with anomaly detection mechanisms.
Key Features

    Real-Time Packet Capture: Intercepts and parses TCP, UDP, and IP layers using Scapy.

    Intrusion Detection (IDS): Implements a SYN Flood/Scan detection algorithm using a threshold-based counter (Hash Table logic).

    GeoIP Mapping: Automatically identifies the geographical location (Country) of external IP addresses via API integration.

    Detailed Logging: Records all network activity with precise timestamps and protocol details to local .txt files.

    Traffic Filtering: Supports targeted monitoring via command-line arguments for specific IPs or ports.

Technical Background

As a Computer Engineering student and IEEEXtreme 2024 competitor (Ranked 37th in Turkey), I focused on optimizing the packet processing speed and ensuring accurate protocol parsing. The project utilizes:

    Python 3.x

    Scapy for packet manipulation.

    Requests for GeoIP API communications.

    Argparse for flexible CLI management.

How to Run

Ensure you have the necessary dependencies installed:
Bash

sudo apt install python3-scapy python3-requests

Run the analyzer with root privileges:
Bash

sudo python3 sniffer.py -o session_logs.txt
