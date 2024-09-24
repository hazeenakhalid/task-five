nmap
# taskfive

## Overview

This repository contains the results of a comprehensive Nmap scan performed on the Metasploitable target machine with the IP address `10.0.2.4`. The scan covers all possible ports to provide a complete overview of the open ports and services running on the target.

## Nmap Scan Details

The Nmap scan was conducted using the following command:

```bash
nmap -p- 10.0.2.4 -oN scan_results.txt
```

- `-p-` specifies that all 65,535 ports should be scanned.
- `10.0.2.4` is the IP address of the Metasploitable target machine.
- `-oN scan_results.txt` saves the scan output in a file named `scan_results.txt`.

## Files

- `scan_results.txt`: Contains the results of the Nmap scan. This file lists all open ports and services found on the target machine.

## Instructions

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/AbhiramT21/taskfive.git
   ```
2. Navigate into the repository directory:
   ```bash
   cd taskfive
   ```
3. Open `scan_results.txt` to view the Nmap scan results:
   ```bash
   cat scan_results.txt
   ```
