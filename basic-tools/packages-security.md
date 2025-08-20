# Security & Firewall

Basic security and firewall tools:
> **Note:** All installation commands require **root access**.

## Tools

- **iptables** – This package provides a command-line utility for configuring Linux kernel firewall rules, allowing control over network traffic filtering and NAT.
  ```bash
  apt install iptables


- **firewalld** – firewall management  
  ```bash
  apt install firewalld

- **fail2ban** – brute-force protection  
  ```bash
  apt install fail2ban

- **unattended-upgrades** – automatic security updates  
  ```bash
  apt install unattended-upgrades

---

## Install All Security Packages

Finally we have:  
```bash
apt -y install iptables firewalld fail2ban unattended-upgrades
