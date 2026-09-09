# Group Policy Lab

## Overview
This folder will contain my Group Policy (GPO) lab. I will document how I created, configured, and applied Group Policy Objects to manage Windows settings across domain-joined computers.

## Skills Demonstrated
- Creating and linking Group Policy Objects (GPOs)
- Enforcing password policies
- Configuring user and computer settings
- Managing software restrictions
- Mapping network drives using GPO
- Deploying desktop backgrounds and security settings
- Understanding GPO inheritance, precedence, and enforcement
- Troubleshooting GPO application issues (gpupdate, gpresult)

Screenshots

1. GPO creation and linking

Configured and linked the IT User Policy to the IT Organizational Unit (OU).
Configured the policy "Prohibit access to Control Panel and PC settings" to restrict domain users from accessing Control Panel and Windows Settings.
<img width="1225" height="763" alt="Screenshot 2026-09-09 105333" src="https://github.com/user-attachments/assets/6e918052-6783-4f5e-8699-3125d4438978" />
<img width="1285" height="737" alt="Screenshot 2026-09-09 110125" src="https://github.com/user-attachments/assets/5ba0b7a9-77c3-4525-a9b9-94504a1e1b31" />

2 Password policy configuration
<img width="1175" height="790" alt="Screenshot 2026-09-09 111641" src="https://github.com/user-attachments/assets/1a879c83-b321-4386-9346-fa8dcddd6d0e" />

- Network drive mapping
- Desktop background deployment
- gpupdate /force results
- gpresult /r output

## Tools Used
- Windows Server 2022
- Group Policy Management Console (GPMC)
- Windows 11
- VMware Workstation 

## Purpose
Group Policy is one of the most powerful tools in Windows enterprise environments. This lab demonstrates my ability to centrally manage user and computer settings across a domain.
