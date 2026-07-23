# Active Directory Administration Lab

![Python](https://img.shields.io/badge/Platform-Windows%20Server-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Overview

The Active Directory Administration Lab is a home-lab project designed to simulate a real enterprise environment. This project demonstrates practical knowledge of Windows Server administration, user management, organizational structures, security policies, and troubleshooting.

The lab focuses on essential system administration tasks commonly performed by IT Support Specialists and Junior System Administrators.

---
## Active Directory Network Topology

The following diagram illustrates the enterprise network used throughout this lab. It shows the Domain Controller, DNS Server, DHCP Server, Firewall, Core Switch, departmental workstations, and IP addressing used to simulate a real-world Windows Server environment.

___

## Objectives

* Create and manage user accounts.
* Configure Organizational Units (OUs).
* Create and manage security groups.
* Configure password policies.
* Manage permissions and access control.
* Simulate account lockouts and password resets.
* Apply troubleshooting techniques.
* Document administrative processes.

---

## Technologies Used

* Windows Server
* Active Directory Domain Services (AD DS)
* Group Policy Management
* DNS
* DHCP
* PowerShell
* Virtual Machines
* Git & GitHub

---

## 📂 Project Structure

```text
Active-Directory-Administration-Lab/

├── README.md
├── docs/
│   ├── Lab-Overview.md
│   ├── Active-Directory-Setup.md
│   ├── User-Management.md
│   ├── Account-Administration.md
│   ├── Group-Management.md
│   └── Troubleshooting.md
│
├── screenshots/
│   ├── aduc-overview.png
│   ├── created-users.png
│   ├── user-properties-paballo-litabe.png
│   ├── account-enabled-disabled.png
│   ├── reset-password.png
│   └── group-memberships.png
│
└── diagrams/
    └── active-directory-lab-topology.png
```

---

## Features

### User Management

* Created user accounts.
* Modified user permissions.
* Reset passwords.
* Disabled and enabled accounts.
* Managed user profiles.

### Organizational Units (OUs)

* Configured department-based OUs.
* Organized users and computers.
* Applied administrative controls.

### Security Groups

* Created security groups.
* Assigned permissions.
* Managed access rights.

### Group Policy

* Configured password policies.
* Enforced security settings.
* Applied user restrictions.

### Troubleshooting

* Resolved login issues.
* Diagnosed network connectivity problems.
* Investigated account lockouts.
* Tested permission inheritance.

---

## Skills Demonstrated

* Active Directory Administration
* User and Group Management
* Windows Server Administration
* Group Policy Management
* Identity and Access Management
* Troubleshooting
* Security Configuration
* Documentation

---

## 📸 Screenshots

### Active Directory Users and Computers – Overview

<img width="800" height="580" alt="Active Directory Users and Computers" src="https://github.com/user-attachments/assets/7fba6586-6dcf-4e8c-8e63-19a4b7f7a41c" />


### Created Users in Active Directory

<img width="828" height="621" alt="Created Users in Active Directory" src="https://github.com/user-attachments/assets/a574bb8e-c97b-4917-afaa-2547a3227373" />

### User Properties – Paballo Litabe

<img width="828" height="574" alt="User Properties" src="https://github.com/user-attachments/assets/c665a4d9-99da-442f-b03b-3d1e51b3e334" />

### User Account Enabled/Disabled

<img width="774" height="560" alt="User Account Enabled:Disabled" src="https://github.com/user-attachments/assets/cba3352f-ab97-4048-9e86-51cc7853d40f" />

### Reset User Password

<img width="736" height="615" alt="Reset User Password " src="https://github.com/user-attachments/assets/fa99057c-9d8e-49f1-8c77-0b5ad3ec56eb" />

### Group Memberships

<img width="828" height="627" alt="Group Membership " src="https://github.com/user-attachments/assets/9b1e45b9-cc77-42c6-a6a5-44341168fc38" />

---

## Future Improvements

* Add DNS and DHCP configuration.
* Integrate Microsoft Entra ID.
* Configure file sharing permissions.
* Create PowerShell automation scripts.
* Expand Group Policy settings.

---

## Author

**Paballo Moipone Litabe**

* LinkedIn: linkedin.com/in/paballo-litabe
* GitHub: github.com/Phabwey

---

## License

This project is licensed under the MIT License.
