\# Milestone 2 — Debian Agent Enrollment



Date: 2026-10-12



\## Completed



\- Connected Debian GNU/Linux 13 to the VirtualBox Host-only network.

\- Configured enp0s8 to obtain its IPv4 address through DHCP.

\- Installed and enabled OpenSSH Server.

\- Verified direct connectivity to Wazuh through enp0s8.

\- Installed Wazuh agent 4.14.8 and enabled its service.



\## Validation



\- Agent name: CyberLab-Debian

\- Agent ID: 001

\- Current endpoint IP: 192.168.56.102 (DHCP; may change)

\- Wazuh manager IP: 192.168.56.10 (static)

\- Local service status: active

\- Dashboard agent status: Active



Agent connectivity is confirmed.

Security event collection and detection scenarios still need validation.



\## Screenshot



!\[Debian agent connected](../screenshots/02-debian-agent-active.png)

