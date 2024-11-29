<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation & Ticketing</h1>
This tutorial demonstrates the setup and usage of prerequisites on the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Post Installation & Ticketing Lifecycle](https://youtu.be/x7hH5rF3Lq4)


<h2>Step By Step</h2>

![image](https://github.com/user-attachments/assets/40922ce8-eb73-4969-b41e-2cdee62a6817)
![Untitled image (10)](https://github.com/user-attachments/assets/34c8b0b5-b767-49da-8af6-6a308cb706a9)


Post Installation Setup
1. Configure Roles:
    * Admin Panel -> Agents -> Roles -> Add "Supreme Admin".
2. Configure Departments:
    * Admin Panel -> Agents -> Departments -> Add "System Administrators".
3. Configure Teams:
    * Admin Panel -> Agents -> Teams -> Add "Level I Support" and "Level II Support".
4. Allow Anyone to Create Tickets:
    * Admin Panel -> Settings -> User Settings -> Uncheck "Require registration and login to create tickets".
5. Configure Agents:
    * Admin Panel -> Agents -> Add New -> Add agents (e.g., Jane, John).
6. Configure Users:
    * Agent Panel -> Users -> Add New -> Add users (e.g., Karen, Ken).
7. Configure SLA:
    * Admin Panel -> Manage -> SLA -> Add:
        * Sev-A (1 hour, 24/7)
        * Sev-B (4 hours, 24/7)
        * Sev-C (8 hours, business hours)
8. Configure Help Topics:
    * Admin Panel -> Manage -> Help Topics -> Add:
        * Business Critical Outage
        * Personal Computer Issues
        * Equipment Request
        * Password Reset


    Tickets and Ticket Lifecycle
1. Practice Creating, Triaging, and Solving Tickets:
    * Example tickets:
        * Sev-A: Entire mobile/online banking system is down -> SysAdmins
        * Sev-B: Accounting department needs Adobe upgrade, broken
        * Sev-B/C: CFO’s laptop seems slow

