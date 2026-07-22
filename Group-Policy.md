# Group Policy Management

## Overview

Group Policy is used to manage and enforce security, desktop, and system settings across users and computers within an Active Directory environment.

This lab demonstrates the creation and application of Group Policy Objects (GPOs) to improve security and standardize configurations.

---

## Group Policy Objects (GPOs)

The following Group Policies were configured:

- Password Policy
- Account Lockout Policy
- Desktop Restrictions
- Windows Update Settings
- Login Script Configuration
- Security Settings

---

## Password Policy Configuration

The following password settings were enforced:

- Minimum password length: 8 characters
- Password complexity enabled
- Maximum password age: 90 days
- Password history enabled

---

## Account Lockout Policy

The following settings were applied:

- Lock account after 5 failed logon attempts
- Lockout duration: 30 minutes
- Reset lockout counter after 30 minutes

---

## Desktop Restrictions

The following restrictions were configured:

- Disabled access to Control Panel
- Restricted Command Prompt access
- Prevented unauthorized software installation
- Limited system setting modifications

---

## Windows Update Configuration

The following update policies were applied:

- Automatic updates enabled
- Scheduled installation configured
- Security updates prioritized

---

## Login Scripts

Login scripts were configured to:

- Map network drives
- Display login messages
- Configure user environments

---

## Administrative Tasks Performed

- Created Group Policy Objects (GPOs).
- Linked GPOs to Organizational Units (OUs).
- Configured security policies.
- Applied desktop restrictions.
- Tested policy inheritance.
- Verified policy enforcement.

---

## Benefits of Group Policy

- Centralized administration.
- Improved security.
- Consistent user experience.
- Reduced administrative workload.
- Standardized system configuration.

---

## Skills Demonstrated

- Group Policy Management
- Active Directory Administration
- Security Configuration
- Windows Server Administration
- Troubleshooting
- System Administration
