# Base Packages

Essential packages to get started with a Debian server:
> **Note:** All installation commands require **root access**.

## Tools

- **vim** – text editor  
  ```bash
  apt install vim

- **less** – view files  
  ```bash
  apt install less

- **curl** – fetch URLs  
  ```bash
  apt install curl

- **wget** – download files  
  ```bash
  apt install wget

- **gnupg / gpg** – GPG key management  
  ```bash
  apt install gnupg gpg

- **ca-certificates** – SSL certificates  
  ```bash
  apt install ca-certificates

- **lsb-release** – detect distro version  
  ```bash
  apt install lsb-release

- **apt-transport-https** – enable HTTPS in apt  
  ```bash
  apt install apt-transport-https

- **git** – version control  
  ```bash
  apt install git

- **zip / unzip** – archive management  
  ```bash
  apt install zip unzip

---

## Install All Base Packages

Finally we have:  
```bash
apt -y install vim nano less curl wget gnupg gpg ca-certificates lsb-release apt-transport-https git zip unzip
