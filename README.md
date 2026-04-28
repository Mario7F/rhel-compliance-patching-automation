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
- service uptime and enablement

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
