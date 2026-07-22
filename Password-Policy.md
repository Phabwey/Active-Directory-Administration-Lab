# Password Policy

## Overview

Password policies are essential for securing user accounts and preventing unauthorized access. This lab demonstrates the configuration of password complexity, password expiration, and account lockout settings in Active Directory.

---

## Password Requirements

The following password policies were configured:

- Minimum password length: 8 characters
- Password complexity enabled
- Password history: 5 previous passwords remembered
- Maximum password age: 90 days
- Minimum password age: 1 day

---

## Password Complexity Rules

Passwords must contain at least three of the following:

- Uppercase letters (A–Z)
- Lowercase letters (a–z)
- Numbers (0–9)
- Special characters (!, @, #, $, %, &)

Example passwords:

- ITSupport@2026
- Admin#1234
- SecurePass!01

---

## Account Lockout Policy

The following account lockout settings were applied:

| Setting | Value |
|----------|----------|
| Invalid logon attempts | 5 |
| Lockout duration | 30 minutes |
| Reset counter after | 30 minutes |

These settings help protect the system from brute-force attacks.

---

## Password Management Tasks

The following administrative tasks were performed:

- Reset user passwords.
- Forced password changes at next logon.
- Unlocked user accounts.
- Updated password policies.
- Tested password complexity requirements.

---

## Security Benefits

The password policy improves security by:

- Protecting user accounts.
- Reducing unauthorized access.
- Preventing weak passwords.
- Minimizing brute-force attacks.
- Enforcing organizational security standards.

---

## Skills Demonstrated

- Password Management
- Security Configuration
- Active Directory Administration
- User Account Management
- Troubleshooting
- Windows Server Administration
