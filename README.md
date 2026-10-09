# CyberLab — Threat Detection and Incident Response

A personal cybersecurity lab by Ulrich TAGHO.

## Objective

Build a hands-on lab to centralize security events, detect suspicious
activity, investigate alerts, and document response procedures.

## Planned Architecture

Three virtual machines hosted in VirtualBox:

| Machine | Allocated RAM | Role |
|---------|---------------|------|
| Wazuh | 8 GB | Central security event collection, analysis, and visualization |
| Debian | 3 GB | Monitored Linux endpoint |
| Windows 11 | 6 GB | Monitored Windows endpoint |

Initially, only Wazuh and one monitored endpoint will run simultaneously
to keep resource usage manageable.

## Planned Detection Scenarios

- Failed SSH login attempts.
- User account creation and privilege changes.
- Changes to sensitive files.
- Monitoring agent shutdown.

Each scenario will document:

- The test procedure.
- The expected result.
- The events and alerts actually observed.
- Investigation steps and remediation.
- Limitations and lessons learned.

## Progress

- [x] Create the GitHub repository.
- [x] Define the initial lab architecture.
- [ ] Configure the lab network.
- [ ] Install the Wazuh central components.
- [ ] Connect the Debian endpoint to Wazuh.
- [ ] Set up and connect the Windows endpoint.
- [ ] Test detection scenarios and investigate alerts.
- [ ] Complete the documentation and final demonstration.

## Project Workflow

Each significant milestone will be documented and committed to GitHub.
LinkedIn updates will share verified progress and lessons learned.

## Testing Scope

All tests will be performed exclusively on lab machines.
Passwords, private keys, tokens, and other secrets will never
be committed to this repository.

## Project Status

The project is in its initial setup phase.
Detection scenarios are planned and have not yet been validated.
