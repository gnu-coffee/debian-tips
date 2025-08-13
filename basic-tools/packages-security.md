# Security & Firewall

Basic security and firewall tools:
> **Note:** All installation commands require **root access**.

## Tools

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
apt -y install firewalld fail2ban unattended-upgrades
