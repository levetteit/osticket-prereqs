# osTicket Deployment on Azure

## Overview

This project documents the deployment and configuration of osTicket on a Microsoft Azure Windows 11 Pro virtual machine.

The lab demonstrates the installation and configuration of a web-based help desk ticketing system using IIS, PHP, MySQL, and HeidiSQL. The purpose of this project is to simulate a real-world IT support environment while developing practical skills in system administration, cloud infrastructure, web server configuration, and troubleshooting.

---

## Technologies 

- Microsoft Azure
- Windows 11 Pro
- Internet Information Services (IIS)
- PHP Manager for IIS
- PHP 7.3.8
- MySQL 5.5
- HeidiSQL
- osTicket v1.15.8

---

## Skills 

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

Azure VM Creation
<p></p>
<img width="1535" height="1024" alt="azure-vm-creation jpg" src="https://github.com/user-attachments/assets/e6f9c0db-15ce-433a-a933-9f42d733c6c9">


---

## Step 2 — Verify Virtual Machine Deployment

After deployment, the virtual machine was successfully provisioned and accessible through Remote Desktop Protocol (RDP).

Azure VM Running
<p></p>
<img width="1672" height="941" alt="azure-vm-deployed jpg" src="https://github.com/user-attachments/assets/f22a6403-b3fe-4c15-90df-e08546fc9761")

---

# IIS Installation & Verification

## Step 3 — Install IIS

Internet Information Services (IIS) was installed to host the osTicket web application.

After installation, localhost successfully displayed the IIS default landing page confirming the web server was operational.

IIS Verification
<p></p>
<img width="1672" height="941" alt="iis-verification jpg" src="https://github.com/user-attachments/assets/1f07f359-5890-4f05-86dd-a76e3adb2dce")

---

# PHP & MySQL Configuration

## Step 4 — Configure PHP and MySQL

PHP Manager, PHP 7.3.8, MySQL 5.5, and required dependencies were installed to support osTicket functionality.

MySQL root credentials were configured during installation.

MySQL Configuration
<p></p>
<img width="1672" height="941" alt="mysql-configuration jpg" src="https://github.com/user-attachments/assets/c088f504-e482-4263-8819-d51b74f75ea8" />


---

# osTicket Installation

## Step 5 — Deploy osTicket

The osTicket installation files were extracted into the IIS web root directory and accessed through localhost.

The installer successfully verified PHP extensions and server prerequisites.

osTicket Prerequisites
<p></p>
<img width="1392" height="1130" alt="osticket-prerequisites jpg" src="https://github.com/user-attachments/assets/2f0f9fca-e0b2-4b8f-905b-8782b088926a" />


---

# Database Configuration

## Step 6 — Create osTicket Database

Using HeidiSQL, the MySQL database for osTicket was created and populated successfully.

The database tables confirmed successful installation and communication between osTicket and MySQL.

Database Created
<p></p>
<img width="1449" height="1085" alt="database-created jpg" src="https://github.com/user-attachments/assets/255505ba-125f-4b30-843f-2e1d669056a9" />


---

# osTicket Verification

## Step 7 — Verify Admin Login Portal

After installation completed successfully, the osTicket admin login portal became accessible.

This confirmed the deployment was functioning properly.

Admin Login
<p></p>
<img width="1448" height="1086" alt="admin-login jpg" src="https://github.com/user-attachments/assets/cbcdc562-0f21-4e45-abc5-d8e0b6484d68" />
<p></p>
<img width="1671" height="941" alt="admin-portal jpg" src="https://github.com/user-attachments/assets/e830fdf4-e5a3-409f-80bc-370f4460f486" />



---

---

# Author

## Jerai Padilla

GitHub:
https://github.com/levetteit
