# Samba Server Setup on RHEL 9

This repository provides a step-by-step guide and configuration files for setting up a **Samba server** on **RHEL 9**. Samba allows file and printer sharing between Linux and Windows systems using the SMB/CIFS protocol.

## 📦 Requirements

- RHEL 9 or compatible Linux distribution
- Root or sudo privileges
- Basic understanding of Linux command line

## 🛠️ Installation Steps

### 1. Install Samba Packages

```bash
sudo dnf install -y samba samba-client samba-common
