<p align="center">
<img src="https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/afe7a47d-ddb0-48c0-98c7-7a84fd47cb99" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

<h3>Log in to your first admin</h3>


<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/63570aa7-36ca-42ca-a753-851957d2413a width="50%" height="auto"/>

<h3>Create new role called Super Saiyan that has complete permission to everything</h3>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/47a214e0-5596-4dd6-8651-3cc876dea99c width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/78c98b7b-2ad5-4c00-a833-ea49173c7739 width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/8c0047ab-a69a-4fe2-9545-090e3dd8951d width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/2ec970cc-bc70-4618-89a3-02fe6ee5b6ae width="50%" height="auto"/>


<h3>Add a new department called System Administrators and leave everything on default</h3>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/f353f57a-b4bf-4e6a-a20e-ccfe06c0f7b4 width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/2e035cc2-6f92-44f2-a235-518a49ac5c11 width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/84b53417-302c-425e-bf84-ea9a50a56db9 width="50%" height="auto"/>

<h3>Add Level II Support team and Accounting Team. Add Summer as a team member for Level II Support</h3>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/d98b77af-933e-47b1-b186-1e73100b0a20 width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/42bc02bc-92fd-4622-8ee9-231d98821558 width="50%" height="auto"/>

<h3>Create new workers</h3>

* Uncheck "send the agent a password reset email" and "require a password change at next log in"

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/c58bcef7-5898-4f5a-ae18-72ce747d72ac width="50%" height="auto"/>

Roger Bob
   
    Email: rogerbob@helpdesk.com
    Username: RogerB
    Password: Bobby R
    Primary Department: System Administrators; Super Saiyan
    Assigned Team: Accounting

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/5700838d-5ac8-4571-969d-6adf235dc8b2 width="50%" height="auto"/>

Jack Daniel

    Email: Jackdaniel@helpdesk.com
    Username: JackD
    Password: DanielJ
    Primary Department: System Administrators; Super Saiyan
    Assigned Team: Level I Support

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/745deb21-8451-45bc-8243-2f337b21f8c4 width="50%" height="auto"/>

Iggy Grump

    Email: IggyGrump@helpdesk.com
    Username: IggyG
    Password: GrumpI
    Primary Department: System Administrators; Super Saiyan
    Assigned Team: Level I Support

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/8d94d3a2-d36b-44d5-ba7a-6a5b5df67ac9 width="50%" height="auto"/>

<img src=https://github.com/Archie735/osTicket-Post-Install-Configuration-/assets/150314129/eb967146-9cf8-4a1d-bb35-9e461821d6c0 width="50%" height="auto"/>

<h3>Create some SLA</h3>

<img src= 

SEV A

    Grace Period: 1 hour
    Schedule: 24/7

    





