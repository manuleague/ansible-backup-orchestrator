# Secure Windows Endpoint Automation: Ansible Backup Orchestrator
---
**Key Technologies Used:** Ansible, WinRM (HTTPS), PowerShell, OpenSSL, SMB/NAS, Hasleo Backup Suite.

This repository contains the source code, Ansible playbooks, and configuration structure for automating Windows workstation backups to a centralized NAS. 

The project demonstrates how to securely orchestrate endpoint backups from a Linux Control Node (Ubuntu WSL) using **Ansible** and **WinRM over HTTPS**. It enforces strict security practices, including self-signed TLS certificate validation, NTLM authentication, and secure credential management using **Ansible Vault**.

### Full Documentation & Step-by-Step Guide
For a detailed breakdown of the setup, configuration, and troubleshooting, read the complete technical article on Medium:

**[Read the full tutorial on Medium here](https://medium.com/@danalacheemanuel/secure-windows-endpoint-automation-orchestrating-nas-backups-with-ansible-and-winrm-bca172084a47)**

