# Networking Tools

Tools for networking and troubleshooting:
> **Note:** All installation commands require **root access**.

## Tools

- **net-tools** – ifconfig, netstat, etc.  
  ```bash
  apt install net-tools

- **iproute2** – modern network commands (ip)  
  ```bash
  apt install iproute2

- **bind9-dnsutils** – dig, nslookup  
  ```bash
  apt install bind9-dnsutils

- **traceroute** – trace network path  
  ```bash
  apt install traceroute

- **tcpdump** – packet capture  
  ```bash
  apt install tcpdump

---

## Install All Networking Packages

Finally we have:  
```bash
apt -y install net-tools iproute2 bind9-dnsutils traceroute tcpdump
