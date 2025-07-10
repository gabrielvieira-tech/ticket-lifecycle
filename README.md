<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration (Not ready yet)</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<img width="1478" height="613" alt="Step 1 Done" src="https://github.com/user-attachments/assets/d0d4f216-1f1e-40e4-8e2e-56fa9eacad8f" />


<p>
Start by creating a ticket as an end-user reporting that the entire mobile/online banking system is down. Then, log in as Help Desk Agent “john” and open the ticket to observe its current properties: Priority, Department, SLA, and Assigned To. Set the ticket’s SLA to Sev-A (1-hour grace period, 24/7 coverage) and assign it to the SysAdmins Department. Try to view or modify the ticket again as john—since the ticket is now under a restricted department, you’ll no longer have access.
<br />

<img width="1456" height="604" alt="Step 2 Done" src="https://github.com/user-attachments/assets/5cf92378-9a91-46d5-9767-f52f3bfc25ae" />


<p>
Go to the Admin Panel and give yourself (john) view access to the SysAdmins department, which includes the Online Banking team. Return to the Agent Panel—you’ll now be able to see the ticket but still won’t be able to change it. Switch to Agent “jane,” who is part of the SysAdmins department, and resolve the ticket from her account.
</p>
<br />

<img width="1479" height="617" alt="Step 3 Done" src="https://github.com/user-attachments/assets/93fb0f3d-8da1-42bc-946d-31eefe042ad1" />


<p>
As the end-user, submit a second ticket stating the accounting department needs an Adobe upgrade and it's currently broken. Log in as john, view the ticket, and assign it the Sev-B SLA (4-hour grace period, 24/7) and the Support(Help Desk) department If not alredy in it. Work and complete this ticket as john.
Then, create a third ticket as the end-user stating that the CFO’s laptop will no longer power on. Again, as john, observe and set the properties—apply the Sev-B SLA and assign it to Support(Help Desk) Resolve this ticket as well.
</p>
<br />

<img width="1274" height="538" alt="Step 4 Done" src="https://github.com/user-attachments/assets/c4bec42d-dc7e-466e-b8e9-12f0be6aaea6" />


<p>
Complete all tickets accordingly. In real-world environments, ticket intake doesn’t always happen through the system interface—requests can come from phone calls, chat apps, emails, web forms, or even someone stopping you in the hallway. It’s common for people to ask for help directly, and while it's fine to fix things immediately, you should always log tickets for every task you perform. This ensures transparency, helps with tracking workload, and supports performance metrics, which are essential for proper IT service management.
</p>
<br />
