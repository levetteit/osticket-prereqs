# osTicket Deployment on Azure

## Overview

This project documents the deployment and configuration of osTicket on a Microsoft Azure Windows 11 Pro virtual machine.

The lab demonstrates the installation and configuration of a web-based help desk ticketing system using IIS, PHP, MySQL, and HeidiSQL. The purpose of this project was to simulate a real-world IT support environment while developing practical skills in system administration, cloud infrastructure, web server configuration, and troubleshooting.

---

## Technologies Used

- Microsoft Azure
- Windows 11 Pro
- Internet Information Services (IIS)
- PHP Manager for IIS
- PHP 7.3.8
- MySQL 5.5
- HeidiSQL
- osTicket v1.15.8

---

## Skills Demonstrated

- Virtual Machine Deployment
- Cloud Computing Fundamentals
- Windows Administration
- IIS Configuration
- PHP Configuration
- Database Administration
- Help Desk System Deployment
- Troubleshooting
- Technical Documentation
- Web Application Hosting

---

# Environment Setup

## Step 1 — Create Azure Virtual Machine

A Windows 11 Pro virtual machine was deployed inside Microsoft Azure to host the osTicket environment.

### Configuration Included:
- Azure Resource Group
- East US Region
- Windows 11 Pro Image
- Public IP Assignment
- RDP Access

![Azure VM Creation]
<p></p>
<img width="1535" height="1024" alt="azure-vm-creation jpg" src="https://github.com/user-attachments/assets/e6f9c0db-15ce-433a-a933-9f42d733c6c9">


---

## Step 2 — Verify Virtual Machine Deployment

After deployment, the virtual machine was successfully provisioned and accessible through Remote Desktop Protocol (RDP).

![Azure VM Running](images/azure-vm-deployed.jpg)

---

# IIS Installation & Verification

## Step 3 — Install IIS

Internet Information Services (IIS) was installed to host the osTicket web application.

After installation, localhost successfully displayed the IIS default landing page confirming the web server was operational.

![IIS Verification](images/iis-verification.jpg)

---

# PHP & MySQL Configuration

## Step 4 — Configure PHP and MySQL

PHP Manager, PHP 7.3.8, MySQL 5.5, and required dependencies were installed to support osTicket functionality.

MySQL root credentials were configured during installation.

![MySQL Configuration](images/mysql-configuration.jpg)

---

# osTicket Installation

## Step 5 — Deploy osTicket

The osTicket installation files were extracted into the IIS web root directory and accessed through localhost.

The installer successfully verified PHP extensions and server prerequisites.

![osTicket Prerequisites](images/osticket-prerequisites.jpg)

---

# Database Configuration

## Step 6 — Create osTicket Database

Using HeidiSQL, the MySQL database for osTicket was created and populated successfully.

The database tables confirmed successful installation and communication between osTicket and MySQL.

![Database Created](images/database-created.jpg)

---

# osTicket Verification

## Step 7 — Verify Admin Login Portal

After installation completed successfully, the osTicket admin login portal became accessible.

This confirmed the deployment was functioning properly.

![Admin Login](images/admin-login.jpg)

---

# Architecture Overview

```text
User Browser
      │
      ▼
IIS Web Server
      │
      ▼
PHP Manager / PHP Runtime
      │
      ▼
osTicket Application
      │
      ▼
MySQL Database
```

---

# Troubleshooting Performed

During the deployment process, several troubleshooting steps were required:

- Verifying IIS installation
- Confirming PHP extensions were enabled
- Ensuring MySQL services were running
- Validating localhost accessibility
- Configuring database permissions
- Verifying osTicket prerequisites

---

# Lessons Learned

This lab provided hands-on experience with:
- Cloud-hosted infrastructure
- Web server administration
- Database configuration
- Ticketing systems
- Troubleshooting methodologies
- Enterprise IT workflows

The project also strengthened documentation and technical communication skills commonly used in IT support and system administration environments.

---

# Author

## Jerai Padilla

GitHub:
https://github.com/levetteit
