# Auto-OVPN
Version 1.0

By: Arjan Sturing

OpenVPN Powershell automation script for Windows 10

Use this script at your own risk!

This script automates the following:

- OpenVPN & Power-RSA (see: https://github.com/arjansturing/Power-RSA)
- Creation of PKI & Server config.
- Creation of Client default config.
- Adding route in Server config.
- Adding DNS server to Server config.
- Adding lookup domain to Server config.
- Creation of passwordless client and config.
- Creation of password protected client and config.
- Creation of CRL / Revoking a client certificate.

Make sure to start an elevated PowerShell Session and set the ExecutionPolicy to RemoteSigned by using the following PS command: Set-ExecutionPolicy -ExecutionPolicy RemoteSigned before running the script!

Automate the world! #PowerShell
