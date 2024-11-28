<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation & Ticketing</h1>
This tutorial demonstrates the setup and usage of prerequisites on the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Post Installation & Ticketing Lifestyle](https://youtu.be/x7hH5rF3Lq4)


<h2>Step By Step</h2>

![Untitled image (5)](https://github.com/user-attachments/assets/48a2ae46-ffcb-415e-b52c-a3d23ddc72df)
![Untitled image (6)](https://github.com/user-attachments/assets/c7cf7fd6-a189-469e-bee6-fbb0924d79d8)

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

