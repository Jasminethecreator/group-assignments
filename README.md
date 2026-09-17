# Assigning Groups to Users in Microsoft Azure's Entra ID

## Objective

Create a security group in Microsoft Entra ID and assign a user as a member to manage access at scale.

## Scenario

This lab simulated setting up group based access for IT staff, so that access to IT tools, admin portals, and tech-related apps could be managed through group membership rather than individual permissions.

## Tasks Completed

- Created a new security group named IT-Staff-Sec-Group, scoped to grant access to IT tools, admin portals, and tech related apps.
- Added Kyle Roberts as a direct member of the group.
- Confirmed the assignment by verifying Kyle Roberts' profile showed one group membership.

## Screenshots

<p align="center">
<img width="700" alt="Security group created" src="https://github.com/user-attachments/assets/fb6badf9-e43a-49a3-b28b-599bb621e1a7" />
</p>
<p align="center"><em>Created the IT-Staff-Sec-Group, scoped to grant access to IT tools, admin portals, and tech-related apps.</em></p>

<p align="center">
<img width="700" alt="Kyle Roberts added to group" src="https://github.com/user-attachments/assets/76476bdf-1dca-4a58-9543-e4bca0d5b035" />
</p>
<p align="center"><em>Confirmed the group was created, with Kyle Roberts added as a direct member.</em></p>

<p align="center">
<img width="700" alt="Profile showing group membership" src="https://github.com/user-attachments/assets/c3e5cd3a-5f87-40bf-b0ec-7f879dab3def" />
</p>
<p align="center"><em>Kyle Roberts' profile now shows one group membership, confirming the assignment.</em></p>

## Skills Demonstrated

- Security Group Management
- Group-Based Access Control
- Identity Administration
- Access Provisioning

## What I Learned

This lab showed the value of managing access through groups instead of one off individual permissions, since it's far easier to add or remove someone from a single group than to track down every individual permission they hold.

## Lab Environment

- Microsoft Azure Entra ID
- Windows 11
