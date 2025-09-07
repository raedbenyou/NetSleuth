# NetSleuth

**NetSleuth** is a next-generation network reconnaissance and analysis tool designed for **ethical cybersecurity research**.  
It helps security professionals and students map networks, analyze host behavior, and visualize connections, with modular features ready for AI-powered enhancements.

## Features
- **Network Scanning:** Detect live hosts on your network using ARP scanning.
- **Host Analysis:** Analyze network devices and their properties.
- **Network Visualization:** Create visual graphs of network topology.
- **Modular Architecture:** Easy to extend with custom scanning and analysis modules.

## Installation
Clone the repository and install required packages:

```bash
git clone https://github.com/DarkPulse/NetSleuth.git
cd NetSleuth
pip install -r requirements.txt

Usage

Example of scanning a network:

python netsleuth/scanner.py

Example of analyzing hosts:

from netsleuth.analyzer import analyze_hosts

hosts = [{'ip':'192.168.1.1','mac':'AA:BB:CC:DD:EE:FF'}]
analyze_hosts(hosts)

Example of visualizing the network:

from netsleuth.visualizer import visualize_network

visualize_network(hosts)

Contributing

Contributions are welcome! Please submit pull requests for bug fixes, new features, or improvements.
Disclaimer

This tool is intended for educational and ethical testing purposes only.
Do not use it on networks you do not own or have explicit permission to test.
=== LICENSE ===

MIT License

Copyright (c) 2025 DarkPulse

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
