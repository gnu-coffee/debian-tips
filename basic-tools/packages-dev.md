# Base Packages

Development packages to get started with a Debian server:
> **Note:** All installation commands require **root access**.

## General Tools

- **build-essential** – Provide compilers and tools for compiling software.
  ```bash
  apt install build-essential

- **libssl-dev** – Development libraries and headers for OpenSSL, required for building applications that use secure communications (TLS/SSL).
  ```bash
  apt install libssl-dev

- **libffi-dev** – Development headers and libraries for the Foreign Function Interface library, used to call functions written in other programming languages (e.g., C) from higher-level languages like Pytho
  ```bash
  apt install libffi-dev libssl-dev libffi-dev

## Python Tools

- **python3** – the Python 3 interpreter, which runs Python code.
  ```bash
  apt install python3

- **python3-pip** – the Python package manager to install libraries and packages from PyPI.
  ```bash
  apt install python3-pip

- **python3** – the Python 3 interpreter, which runs Python code.
  ```bash
  apt install python3

---

## Install general Development Packages

Finally we have:  
```bash
apt -y install build-essential
```
---

## Install python based Development Packages

Finally we have:  
```bash
apt -y install python3 python3-venv python3-pip
```
