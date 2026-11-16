
# Linux Infrastructure Automation with Ansible

## Overview

A Linux infrastructure automation project demonstrating
configuration management, package deployment, patch
management and server administration using Ansible.

The project is designed around a lab environment running
AlmaLinux servers, with AWX providing centralised job
execution and scheduling.

## Architecture

- GitHub: Source code management and version control
- Ansible: Infrastructure automation and configuration management
- AWX: Centralised automation dashboard and job scheduling
- K3s: Kubernetes platform hosting AWX
- AlmaLinux: Managed Linux servers
- SSH: Secure communication with managed hosts

## Features

- Linux server connectivity and health checks
- Automated package installation and removal
- Package updates and security patching
- Standard Linux configuration baseline
- Reusable Ansible roles
- Configuration drift correction
- AWX job templates and scheduled execution
- Git-based automation workflows

## Technology Stack

- AlmaLinux
- Ansible
- AWX
- K3s
- Git
- GitLab CI/CD
- YAML
- Linux / SSH

## Repository Structure

See the project folders for inventories, playbooks,
reusable roles, execution environment and documentation.

## Lab Environment

The project is developed and tested using a virtualised
Linux lab environment.

Example inventory files are provided. Configure your
own host addresses and SSH credentials before running
the playbooks.

## Future Improvements

- Multi-environment inventory management
- Automated patch reporting
- Compliance validation
- Automated configuration drift detection
- AWX workflow approvals
- Monitoring integration

## Disclaimer

This is a personal portfolio project developed in a
test lab environment. It does not contain company
infrastructure details or confidential information.
