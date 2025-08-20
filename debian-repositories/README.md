# Debian Tips - Repositories

This folder contains configuration files for Debian Stable/Testing/etc repositories.

## Debian Repositories

This project includes a sample **sources.list** file for Debian Stable servers.

- The provided configuration uses **only the `main` component**, which contains
  100% Free Software according to the [Debian Free Software Guidelines (DFSG)](https://www.debian.org/social_contract#guidelines).
- This is the safest option for production environments.

### Adding `contrib` and `non-free`
You may also enable the `contrib` and `non-free` components if you require:
- Software that depends on non-free parts (`contrib`)
- Software that is itself non-free (`non-free`)

These components are **part of the official Debian archive** but **are not considered official Debian software** because they do not fully comply with the DFSG.

**Example (enabling contrib and non-free):**
```
deb http://deb.debian.org/debian stable main contrib non-free
deb-src http://deb.debian.org/debian stable main contrib non-free
```

## Usage
To apply this repository configuration to your Debian Stable server:

1. Copy the `sources.list` file to `/etc/apt/sources.list` **as root**:
```
cp repositories/sources.list /etc/apt/sources.list
```
2. Update package lists:
```
apt update
```

### File location
The actual `sources.list` file is located in this folder:

```
repositories/sources.list
```
