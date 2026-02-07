<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />

<p>

</p>
</p>
<p>
Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup.
first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>
<img width="481" height="206" alt="image" src="https://github.com/user-attachments/assets/23cb952b-63a2-4217-ad32-662165901b1f" />
</p>
<p>
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<p>
<img <img width="380" height="314" alt="image" src="https://github.com/user-attachments/assets/f91d08df-0059-499b-8dd7-3e71047447ff" />
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 
</p>
<br />
<p>
<img <img width="382" height="284" alt="image" src="https://github.com/user-attachments/assets/9ede2d06-d623-4f21-b127-e2a06aeb7e50" />
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<img <img width="382" height="288" alt="image" src="https://github.com/user-attachments/assets/5cae2973-9937-4c15-903e-9b1633c9f541" />
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<img <img width="317" height="310" alt="image" src="https://github.com/user-attachments/assets/7bacfbd0-14be-4e66-aac6-5eecf1c37747" />
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<img <img width="335" height="148" alt="image" src="https://github.com/user-attachments/assets/886e14de-6ad3-4c7c-abe2-7ce3f916f663" />
</p>
</p>
</p>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
</p>
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
</p>
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
</p>
Sev-C (Grace Period: 8 hours, Business Hours) 
</p>
<br />
<img <img width="322" height="232" alt="image" src="https://github.com/user-attachments/assets/8f5b4d1f-16ce-4510-8c72-c33c0fa99f3d"/>
</p>
<img width="486" height="242" alt="image" src="https://github.com/user-attachments/assets/72506ede-83a2-4393-a4c1-83bf24619af2" />
</p>
</p>
<p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
</p>
Business Critical Outage
</p>
Personal Computer Issues
</p>
Equipment Request
</p>
Password Reset
</p>
Other
</p>
<img <img width="428" height="311" alt="image" src="https://github.com/user-attachments/assets/488bc932-e1fe-405a-a5a5-075899ea6a1d" />
</p>
<img width="431" height="290" alt="image" src="https://github.com/user-attachments/assets/a4dcd1bb-e46a-416f-baf8-5b717f5608cb" />
</p>
