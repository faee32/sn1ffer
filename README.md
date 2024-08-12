# sn1ffer
Overview:

This project is a network sniffer tool in Python. It captures and analyzes network traffic on the host, providing detailed information about each packet.

Features:

    Captures network packets in real-time.
    Provides information about each packet, including source and destination IP addresses, protocol.

Installation:

Install the required dependencies:

    sudo apt install python3-scapy

Usage:

Navigate to the project directory:

    cd sn1ffer

Run the network sniffer script:

    python3 sn1ffer.py <interface>

The script will start capturing network packets and then make a log file in the same direcory.
