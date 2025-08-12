## Project Title: Python-PortScanner ##

# Project Description:

A simple Python-based TCP port scanner that checks for open ports on a target system. This tool is useful for network administrators, cybersecurity students, and home lab enthusiasts to identify which services are 
running on a host.  

# How It Works

- Loops through a range of ports (1–1024 by default).
- Attempts a TCP connection to each port.
- If the connection is successful, the port is marked as open.
- Results are printed to the console.

# Features

- Scans ports 1–1024 (configurable range).
- Lightweight and easy to use.
- Displays all open ports found.
- Uses Python’s built-in socket library (no extra dependencies).



