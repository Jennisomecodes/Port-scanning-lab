 Port Scanner

A simple Python-based port scanner developed as a cybersecurity learning project.

 Project Overview

A port scanner is a cybersecurity tool used to check a computer or server for network ports that are accepting connections.

This project demonstrates how Python can be used to test network ports, identify open ports, and display the results.

 Objective

The objectives of this project are to:

Understand basic network ports and services

Learn the fundamentals of network reconnaissance

Practice Python network programming

Identify open ports on an authorized test host

Record and interpret scan results

Test Target

The scanner was tested against:

scanme.nmap.org

This is a public test host provided by the Nmap project for learning and practicing network scanning.

 Sample Results

Results for scanme.nmap.org:
Open ports: [21, 22, 80]

Results for scanme.nmap.org:
Open ports: [22, 80]

Common ports identified

Port

Common Service

Purpose

21

FTP

File transfer

22

SSH

Secure remote access

80

HTTP

Web traffic

An open port means that the target host is accepting network connections on that port.

 How It Works

Target Host
    ↓
Try selected ports
    ↓
Check whether a connection succeeds
    ↓
Store open ports
    ↓
Display results

The scanner:

Receives a target hostname.

Attempts connections to selected ports.

Determines which ports are reachable/open.

Stores the open ports.

Displays the results.

 Why Results May Differ

Different scans may produce slightly different results. For example, one scan may show port 21 as open while another may not.

Possible reasons include:

Changes in the target's network service

Temporary service availability

Server configuration changes

Network conditions

Different scanner settings

 Skills Demonstrated

Python

Network scanning

TCP/IP fundamentals

Ports and network services

Basic cybersecurity reconnaissance

Python socket/network programming

Result handling and documentation

 Future Improvements

Planned improvements include:

Custom port ranges

Service detection

Better error handling

Command-line arguments

TXT/CSV/JSON result export

Graphical user interface

 Ethical Use

Only scan systems that you own or have explicit permission to test.

Unauthorized port scanning may violate organizational policies or applicable laws.

 Project Files

port_scanner/
├── scanner.py
├── scan_results.txt
└── README.md

 Author

Chisom Jennifer Afoaku

Cybersecurity Student | Cybersecurity Intern | Aspiring Cybersecurity Professional

<img width="699" height="500" alt="Screenshot 2026-07-13 140613" src="https://github.com/user-attachments/assets/4d254573-365b-4fdb-8446-370acca4c0a8" />
