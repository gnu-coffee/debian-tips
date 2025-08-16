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

- **iputils-ping** – provides the ping command to check network connectivity between hosts.
  ```bash
  apt install iputils-ping

- **ncat** – a network utility (part of Nmap) for reading and writing data across networks; can act as a client or server for TCP/UDP connections.
  ```bash
  apt install ncat

--

## Install All Networking Packages

Finally we have:  
```bash
apt -y install net-tools iproute2 bind9-dnsutils traceroute tcpdump iputils-ping ncat
