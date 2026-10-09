\# Milestone 1 — Wazuh Deployment



Date: 2026-10-09



\## Completed



\- Imported the official Wazuh 4.14.8 OVA into VirtualBox 7.2.6.

\- Named the virtual machine CyberLab-Wazuh.

\- Allocated 8 GB of RAM and 4 virtual CPUs.

\- Configured adapter 1 as NAT for outbound connectivity.

\- Configured adapter 2 as Host-only for lab communication.

\- Successfully accessed the Wazuh dashboard from the Windows host.

\- Changed the default Linux password for wazuh-user.



\## Network



The observed Host-only address is 192.168.56.101/24.

This address is currently assigned dynamically and may change.



Dashboard: https://192.168.56.101



\## Validation



The dashboard is accessible. No endpoint agents are registered yet.

The displayed alert counts do not, by themselves, prove an attack.



\## Remaining Tasks



\- Change the default dashboard administrator password.

\- Configure a stable lab address.

\- Connect the Debian endpoint and validate event collection.



\## Screenshot



!\[Wazuh dashboard](../screenshots/01-wazuh-dashboard.png)

