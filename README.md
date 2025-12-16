# Nutanix Remote Network Audit (Prism API)

Python-based automation that remotely connects to Nutanix Prism using REST APIs to audit virtual machine networking and generate a CSV report for network visibility, troubleshooting, and documentation.

## Description
This script collects virtual machine network interface details and maps each VM to its associated subnets. The data is exported into a CSV file, helping administrators understand network layouts, support troubleshooting, maintain documentation, and perform network audits in Nutanix environments.

## Key Features
- Remote connection to Nutanix Prism (API-based, read-only)
- VM to subnet network mapping
- Generates CSV reports for auditing and documentation
- Designed for remote administrators

## How to Run
```bash
python prism_network_audit.py --prism <PRISM_IP> --user <USERNAME> --password <PASSWORD>
