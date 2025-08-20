# Base Packages

Essential packages to get started with a Debian server:
> **Note:** All installation commands require **root access**.

## Tools

- **vim** – text editor  
  ```bash
  apt install vim

- **tree** – list contents of directories in a tree-like format
  ```bash
  apt install tree

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

- **bash-completion** – auto bash-completion
  ```bash
  apt install bash-completion

- **util-linux** – This package contains a collection of essential system utilities for managing Linux systems, such as disk partitioning, login, mounting, and more.
  ```bash
  apt install util-linux

- **grub-common** – This package provides common files for the GRUB bootloader, including modules, utilities, and localization support.
  ```bash
  apt install grub-common

- **bsdextrautils** – This package provides a set of additional utilities from the BSD operating systems, such as tools for text processing and system management.
  ```bash
  apt install bsdextrautils

- **mokutil** – This package provides a utility to manage Machine Owner Keys (MOK) in UEFI Secure Boot environments.
  ```bash
  apt install mokutil


---

## Install All Base Packages

Finally we have:  
```bash
apt -y install vim tree less curl wget gnupg gpg ca-certificates lsb-release apt-transport-https git zip unzip bash-completion util-linux grub-common bsdextrautils mokutil
