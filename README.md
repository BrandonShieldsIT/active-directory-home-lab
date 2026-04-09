# 🔧 Active Directory User Management & Troubleshooting Lab

##  Overview
This project simulates real-world help desk scenarios using Active Directory in a Windows Server environment. The focus is on user account management, troubleshooting login issues, and restoring user access in an enterprise setting.

---

##  Scenario

A user reports they are unable to log into their workstation after multiple failed login attempts. This lab demonstrates how a help desk technician would diagnose and resolve the issue using Active Directory.

---

##  Tools & Technologies Used

- Windows Server (Domain Controller)
- Active Directory Users & Computers (ADUC)
- Windows 10 Client Machine
- PowerShell (basic commands)

---

##  Lab Setup

- Configured a Windows Server as a Domain Controller
- Created a domain environment
- Joined a Windows 10 machine to the domain
- Created multiple user accounts and groups

---

##  Problem

A user account becomes locked after multiple incorrect password attempts, preventing login access.

---

##  Troubleshooting Process

1. Verified the client machine is connected to the domain
2. Attempted login to replicate the issue
3. Accessed Active Directory Users & Computers (ADUC)
4. Located the affected user account
5. Identified that the account was locked out
6. Reviewed account properties and security settings

---

##  Resolution

- Unlocked the user account in Active Directory
- Reset the user’s password
- Verified successful login on the client machine

---

##  Screenshots

> (Add your screenshots here — examples below)

- User account locked in ADUC
- Account properties showing lockout status
- Password reset process
- Successful login after resolution

---

##  Skills Demonstrated

- Active Directory user account management
- Troubleshooting account lockouts
- Password reset procedures
- Identifying and resolving login issues
- Basic help desk workflow

---

##  What I Learned

- How account lockout policies impact user access
- The importance of structured troubleshooting
- How to quickly restore user productivity in a business environment

---

##  Future Improvements

- Automate account unlocks using PowerShell
- Implement Group Policy for account lockout thresholds
- Expand lab to include additional help desk scenarios
