# rhel-compliance-patching-automation
Ansible automation framework for Red Hat Enterprise Linux (RHEL), service health, patch management, compliance validation, remediation and reporting

## Overview

This project was created to showcase Ansible's ability to validate Linux systems compliance, patch posture, service health and perform basic remediation across multiple RHEL9 systems.

The environment uses CENTOS as the control node running Ansible Core to manage multiple RHEL 9 hosts through SSH and privilege escalation.

The goal of this project is to reduce manual operational work, improve consistency, improve consistency and provide a repeatable compliance validation across the environment.

---

## How does this resolve Business Problems?

Manual validation of Linux systems for compliance, patching and service health is time consuming

As a system administrator myself, manual checks across a enterprise environment (50+ servers) can lead to fatigue and missed checks

We are required to verify the services below on a daily basis:

- SELinux enforcement
- firewalld state
- auditd health
- chronyd status
- patch/update posture
- kernel version consistency
- required package presence
- service uptime and health

Performing this manually across multiple systems increases the risk of configuration drift, missed findings, and delayed remediation.

With all being said, this project solves the problem using repeatable Ansible automation.

## Solution 

This automation framework performs:

- Service validation across managed hosts
- Basic compliance checking
- Patch validation and update awareness
- Compliance report generation
- Automated remediation of common operational issues

The project ensures systems remain aligned with expected operational and security baselines

---

## Environment

### Control Node

- CentOS
- Ansible Core
- SSH-based management
- Sudo privilege escalation

### Managed Hosts

- Red Hat Enterprised Linux 9
- Multiple target systems
- Enterprised Linux service validation and remediation

## Technologies Used

- Ansible Core
- YAML
- Linux System Administration
- RHEL 9
- CentOS
- SSH
- systemd
- SELinux
- firewalld
- auditd
- chronyd
- Bash
- Troubleshooting

## Proof of Work

Below are terminal outputs demonstrating the automation running across RHEL 9 systems

More detail information along with troubleshooting in the "screenshots" folder


### Service Validation

<img width="1171" height="667" alt="Screenshot 2026-04-26 at 11 16 11 PM" src="https://github.com/user-attachments/assets/71e20fcb-5b03-42c2-90e6-fa2d694317ee" />


## Compliance Check

<img width="1419" height="838" alt="Screenshot 2026-04-27 at 9 02 33 PM" src="https://github.com/user-attachments/assets/e6d2777f-e683-4dde-8ab2-42b48e7e1a38" />

## Patching Validation 

<img width="1517" height="839" alt="Screenshot 2026-04-27 at 9 14 03 PM" src="https://github.com/user-attachments/assets/3b0751ea-e55a-4045-84e6-bf720b8536f3" />

<img width="1390" height="237" alt="Screenshot 2026-04-27 at 9 14 16 PM" src="https://github.com/user-attachments/assets/eb797bdf-2540-4414-b8ff-7d46199b213c" />

## Compliance Report

<img width="1450" height="468" alt="Screenshot 2026-04-27 at 9 57 35 PM" src="https://github.com/user-attachments/assets/281dd1ba-8d68-4305-9daa-f26a3100fb79" />

## Remediation 

<img width="1353" height="853" alt="Screenshot 2026-04-28 at 8 13 33 AM" src="https://github.com/user-attachments/assets/452b57b2-0528-4802-98ce-124935bf6b0e" />



