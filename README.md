# Reverse DNS Scan Script

This script performs a reverse DNS scan over a specified IP range.

## Features

- **Reverse DNS Lookup**: Resolves each IP address in the range to find associated domain names.
- **Output Filtering**: Displays only resolved domain names or notifies if no domain is found for an IP.

## Prerequisites

- **host**: The script uses the `host` command to perform reverse DNS lookups. Ensure it’s installed (use `dnsutils` on Debian-based systems if needed).
- **Bash Shell**: Compatible with Unix-like systems (Linux, macOS).

## Usage

Run the script with a start and end IP address to specify the scan range:

```bash
./reverse_dns_scan.sh <start_ip> <end_ip>
```

### Example

```bash
./reverse_dns_scan.sh 37.59.174.224 37.59.174.239
```

## Notes

- **Permission**: Ensure you have authorization to scan the IP range.

## Author

Written by tyto.
