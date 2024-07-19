Packet Analyzer
Overview

The Packet Analyzer is a tool designed to capture and analyze network packets. This project leverages the Scapy library to sniff network traffic and display key information such as source and destination IP addresses, TCP ports, and payload data. This tool is intended for educational purposes to demonstrate network analysis techniques and the importance of network security.
Features

    Packet Sniffing: Captures live network packets.
    Detailed Analysis: Displays source and destination IP addresses, TCP source and destination ports, and raw data from the packets.
    Educational Use: Provides hands-on experience with network traffic analysis.

Installation

    Clone the Repository:

    bash

git clone https://github.com/yourusername/packet-analyzer.git
cd packet-analyzer

Install Dependencies:
Ensure you have Python installed. Then, install the required packages using pip:

bash

    pip install scapy

    Install Npcap:
    To capture network packets on Windows, install Npcap, which is required for Scapy to access network interfaces.

Usage

    Run the Packet Analyzer:

    bash

    python packet_analyzer.py

    Stopping the Analyzer:
    To stop the packet analyzer, you can use Ctrl + C in your command line interface.

    Viewing Packet Data:
    The output will display live packet information, including IP addresses, TCP ports, and payload data, in your terminal.

Important Notes

    Ethical Considerations: Use this tool responsibly and ensure you have permission to capture and analyze network traffic on the network you are monitoring.
    Permissions: Always seek explicit authorization before capturing network traffic to avoid legal and ethical issues.

Contribution

Feel free to fork the repository and submit pull requests if you have enhancements or additional features you’d like to contribute.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Contact

For any questions or feedback, please contact me at dominicbass096@gmial.com
