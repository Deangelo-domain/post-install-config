# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1/ How to Configure Roles
- Item 2/ How to Configure Departments 
- Item 3/ How to Configure Teams
- Item 4/ How to Allow anyone to create tickets
- Item 5/ How to Configure Agents (workers)
- Item 6/ How to Configure Users (customers)

<h2>Configuration Steps</h2>

<p>
<img width="970" height="995" alt="Screenshot 2025-07-30 180256" src="https://github.com/user-attachments/assets/7dec2a72-4658-405c-9aa4-86aa3c39ecf4" />
<img width="1001" height="703" alt="Screenshot 2025-07-30 180931" src="https://github.com/user-attachments/assets/ac06bfac-9871-4b9f-8ec4-11285825bf00" />
<img width="1004" height="696" alt="Screenshot 2025-07-30 181053" src="https://github.com/user-attachments/assets/2969ad58-2bc2-4e6c-962a-16a634556460" />

</p>
<p>
Item 1 - How to Configure Roles

Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

</p>
<br />

<p>
><img width="985" height="687" alt="Screenshot 2025-07-30 181414" src="https://github.com/user-attachments/assets/870633e8-436b-4f13-ad3e-8d772d7eaaf5" />

</p>
<p>
Item 2 -Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins
</p>
<br />

<p>
<img width="1273" height="681" alt="Screenshot 2025-07-30 181519" src="https://github.com/user-attachments/assets/ba43983a-9468-40d8-8134-2bdbb2e61671" />

</p>
<p>
Item 3 - Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
</p>
<br />
><img width="975" height="958" alt="Screenshot 2025-07-30 181755" src="https://github.com/user-attachments/assets/ffe9cbd1-470e-4484-81c2-1af0803aef25" />

</p>
<p>
Item 4- Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 
  

</p><img width="974" height="998" alt="Screenshot 2025-07-30 182313" src="https://github.com/user-attachments/assets/92d4490f-d3a0-4f18-99db-46027949eee2" />

<p>
Item 5 - Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

 ><img width="967" height="784" alt="Screenshot 2025-07-30 183024" src="https://github.com/user-attachments/assets/8eef5304-ef71-4fc4-b8d0-be6b5d3b6988" />

</p>
<p>
Item 6 Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
