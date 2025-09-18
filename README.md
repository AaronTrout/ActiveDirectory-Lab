# ActiveDirectory-Lab
Windows Server 2022 AD Lab with Windows 10/11 Clients

📌 Overview

This project demonstrates the setup of a Windows Server 2022 Active Directory Domain Controller with Windows 10 and Windows 11 client machines in VMware Workstation Pro.
The goal is to showcase practical IT and cybersecurity skills, including domain management, user authentication, and Group Policy configuration.

⚙️ Lab Environment

VMware Workstation Pro

Windows Server 2022 (Domain Controller)

Windows 10 Enterprise x64 (Client 1)

Windows 11 Enterprise x64 (Client 2)

🔹 Step 1: Install Active Directory Domain Services (AD DS)

Opened Server Manager → Add Roles and Features.

Selected Active Directory Domain Services (AD DS).

📸 Screenshot:


🔹 Step 2: Promote Server to Domain Controller

Configured the server as a new forest with domain name: homelab.local.

Restarted after installation.

📸 Screenshot:


🔹 Step 3: Verify Domain Controller

Logged back in as Domain Administrator.

Confirmed Active Directory Users and Computers (ADUC) is available.

📸 Screenshot:


🔹 Step 4: Join Windows 10 Client to the Domain

Changed computer settings → joined homelab.local domain.

Logged in using domain credentials.

📸 Screenshot:


🔹 Step 5: Join Windows 11 Client to the Domain

Same steps as Windows 10 → joined homelab.local.

Verified login with domain account.

📸 Screenshot:


🔹 Step 6: Group Policy Test

Created a Group Policy Object (GPO) to enforce a desktop wallpaper.

Verified settings applied on both Windows 10 and 11 clients.

📸 Screenshot:


✅ Results

Successfully configured a working Active Directory domain environment.

Verified domain joins, user authentication, and Group Policy enforcement.

📚 Skills Demonstrated

Windows Server Administration

Active Directory & Domain Management

User & Group Management

Group Policy Objects (GPOs)

VMware Virtualization

Documentation & GitHub Portfolio Building
