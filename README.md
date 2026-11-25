# AWS EC2 Linux Web Server Administration

A hands-on Linux System Administration project focused on provisioning, configuring, securing, monitoring, and troubleshooting an Ubuntu web server hosted on AWS EC2.

## Project Overview

This project demonstrates practical Linux server administration and AWS infrastructure fundamentals through the deployment and management of an Ubuntu-based web server using Nginx.

The implementation covers remote server administration, web server configuration, security practices, service management, monitoring, and troubleshooting.

**Project status:** In Progress

## Objectives

- Understand AWS EC2 instance provisioning.
- Configure secure SSH access to a Linux server.
- Install and configure Nginx.
- Configure network access using AWS Security Groups.
- Manage Linux services using systemctl.
- Monitor CPU, memory, disk and filesystem utilisation.
- Analyse system and application logs.
- Perform basic Linux server troubleshooting.

## Technology Stack

| Technology | Purpose |
|---|---|
| AWS EC2 | Virtual Linux server |
| Ubuntu Server | Operating system |
| Nginx | Web server |
| SSH | Remote administration |
| Bash | Automation |
| Git and GitHub | Version control and documentation |

## Proposed Architecture

```text
             Internet
                 |
                 v
          Web Browser
                 |
                 v
        AWS Security Group
                 |
                 v
          AWS EC2 Instance
                 |
          Ubuntu Server
                 |
          +------+------+
          |             |
        Nginx          SSH
          |             |
     Web Content   Administration
          |
      Monitoring
```

## Project Implementation

The project will be completed in the following stages:

- [ ] Stage 1: AWS account and EC2 preparation
- [ ] Stage 2: Launch Ubuntu EC2 instance
- [ ] Stage 3: Configure secure SSH connectivity
- [ ] Stage 4: Install and configure Nginx
- [ ] Stage 5: Configure network security
- [ ] Stage 6: Verify web server availability
- [ ] Stage 7: Create Bash server health-check scripts
- [ ] Stage 8: Monitor Linux services and system resources
- [ ] Stage 9: Perform troubleshooting exercises
- [ ] Stage 10: Document implementation and test results

## Linux Commands and Administration

The project will include practical use of:

- `df -h` — Filesystem disk utilisation
- `df -i` — Inode utilisation
- `free -m` — Memory utilisation
- `du` — Directory disk usage
- `systemctl` — Service management
- `journalctl` — System log investigation
- `ps` and `top` — Process monitoring
- `ss` — Network socket inspection

## Security Considerations

- Use SSH key-based authentication.
- Restrict SSH access to trusted IP addresses.
- Allow only required inbound ports.
- Avoid exposing unnecessary services.
- Never commit private keys, passwords or AWS credentials to GitHub.

## Repository Structure

```text
aws-ec2-linux-web-server/
├── README.md
├── architecture/
├── docs/
├── scripts/
├── screenshots/
└── cleanup.md
```

## Testing and Evidence

Implementation screenshots, configuration details, test results, and troubleshooting notes will be added as each stage is completed.

## Cost and Cleanup

AWS resources will be checked for potential charges before deployment. Resources created for testing will be stopped or terminated when no longer required, as appropriate.

## Author

**Nehali Rane**

GitHub: [NehaliRane](https://github.com/NehaliRane)

---

This repository is a practical learning and portfolio project demonstrating Linux System Administration and AWS infrastructure skills.
