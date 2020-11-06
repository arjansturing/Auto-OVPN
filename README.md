# Auto-OVPN
Version 1.0

By: Arjan Sturing

OpenVPN automation Powershell script for Windows, OpenVPN automation Powershell script for Windows, Auto-OVPN for OpenVPN 2.5.0 can be found here: https://github.com/arjansturing/Auto-OVPN-2.0

Use this script at your own risk!

This script automates the following:

- Installation of OpenVPN 2.4.9 & Power-RSA (see: https://github.com/arjansturing/Power-RSA)
- Creation of basic PKI & Server config.
- Creation of Client default config.
- Adding route in Server config.
- Adding DNS server to Server config.
- Adding lookup domain to Server config.
- Creation of passwordless client and config.
- Creation of password protected client and config.
- Creation of CRL / Revoking a client certificate.

Make sure to start an elevated PowerShell Session and set the ExecutionPolicy to RemoteSigned by using the following PS command: Set-ExecutionPolicy -ExecutionPolicy RemoteSigned before running the script!

Automate the world! #PowerShell

//This script is tested on Windows 10 (Build: 2004) with PowerShell version 5.1
