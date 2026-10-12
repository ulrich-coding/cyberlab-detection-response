\# SSH Detection — Invalid User



Date: 2026-10-12



\## Objective



Validate SSH security event collection from Debian to Wazuh.



\## Test



A single SSH login attempt was made from the Windows host

(192.168.56.1) to Debian (192.168.56.102), using the nonexistent

user cyberlab-test and a fictitious password.



\## Evidence



\- The SSH client reported Permission denied.

\- Debian's journal recorded the invalid user and failed password.

\- Wazuh displayed alerts for agent 001 (CyberLab-Debian),

&#x20; including rule 5710, level 5.

\- An inspected alert's full\_log contained cyberlab-test

&#x20; and source IP 192.168.56.1.



\## Conclusion



SSH event collection and detection of an invalid-user login

attempt were validated. This single attempt does not

demonstrate brute-force detection or automated response.



\## Screenshot



!\[SSH alert details](../screenshots/03-debian-ssh-alert-details.png)

