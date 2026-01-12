# Active-Directory-VM-Lab
Configuring Active Directory using EC2 on AWS
# Hands-On Lab: Active Directory Setup and Configuration on Windows Server

## Overview
This lab demonstrates the setup and configuration of **Active Directory Domain Services (AD DS)** on a Windows Server virtual machine. The lab covers installing server roles, configuring DNS, and performing identity and access management tasks using **Active Directory Users and Computers (ADUC)**.

---

## Lab Environment
- **Operating System:** Windows Server (VM)
- **Management Tool:** Server Manager
- **Directory Service:** Active Directory Domain Services (AD DS)
- **DNS:** Integrated DNS Server
- **Domain:** `skool.local`

---

## Objectives
- Install and configure Active Directory Domain Services
- Verify DNS integration
- Access and manage Active Directory Users and Computers
- Create security groups for role-based access control (RBAC)

---

## Step 1: Server Manager Dashboard (Initial Setup)

The Server Manager dashboard is used to verify server health and begin configuration.

![Server Manager Dashboard](Screenshot%202026-01-11%20at%204.37.48 PM.png)

**Key Observations:**
- Local server is online and manageable
- AD DS, DNS, and File Services are visible
- Server is ready for role configuration

---

## Step 2: Install Active Directory Domain Services

Using **Add Roles and Features Wizard**, Active Directory Domain Services is selected and installed.

![Add Roles and Features – Server Roles](Screenshot%202026-01-11%20at%204.38.05 PM.png)

**Installed Roles:**
- Active Directory Domain Services (AD DS)
- DNS Server
- File and Storage Services

**Outcome:**  
The server is promoted to a **Domain Controller** and configured to host directory services.

---

## Step 3: Verify Domain and Directory Services

After installation, **Active Directory Users and Computers (ADUC)** is launched to confirm domain creation.

![Active Directory Users and Computers](Screenshot%202026-01-11%20at%204.41.42 PM.png)

**Verified Items:**
- Domain: `skool.local`
- Default containers and organizational units
- Directory services are functioning correctly

---

## Step 4: Create a Security Group

A security group is created to demonstrate **group-based access control**.

![Create New Active Directory Group](Screenshot%202026-01-11%20at%204.42.46 PM.png)

**Group Configuration:**
- **Group Name:** `SkoolGroup`
- **Group Scope:** Global
- **Group Type:** Security

**Purpose:**  
This group can be used to assign permissions, enforce policies, and manage access to resources.

---

## Security & Identity Concepts Demonstrated
- Centralized identity management
- Active Directory Domain Services (AD DS)
- DNS integration with authentication services
- Role-Based Access Control (RBAC)
- Secure group-based permission management

---

## Skills Demonstrated
- Windows Server Administration
- Active Directory setup and configuration
- DNS services integration
- User and group management
- Enterprise identity and access management

---

## Conclusion
This lab demonstrates foundational skills in deploying and managing **Active Directory** within a Windows Server environment. These skills are essential for roles in **system administration, cybersecurity, IAM, SOC operations, and IT support**.

---



