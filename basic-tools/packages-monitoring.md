# Monitoring Tools

Essential tools to monitor system performance.  
> **Note:** All installation commands require **root access**.

## Tools

- **htop** – interactive process viewer  
  ```bash
  apt install htop

- **iotop** – monitor disk I/O usage
  ```bash
  apt install iotop

- **iftop** – monitor network bandwidth per connection
  ```bash
  apt install iftop

- **sysstat** – includes iostat, mpstat, sar
  ```bash
  apt install sysstat

- **glances** – comprehensive system monitoring
  ```bash
  apt install glances

- **procps** – memory, CPU, I/O statistics
  ```bash
  apt install procps

---

## Install All Monitoring Packages

Finally we have:  
```bash
apt -y install htop iotop iftop sysstat glances procps
