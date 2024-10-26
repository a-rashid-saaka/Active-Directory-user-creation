
<h1 align="center"> Active Directory Doamin User Generation </h1>
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>



<p>Welcome to the "Active Directory Domain User Generation" project. In this project, we will develop user accounts using a PowerShell script. This script will help organize and populate our domain with user profiles, preparing us for future simulated scenarios. </p>

<h2>Prerequisites</h2>

- <a href="https://github.com/a-rashid-saaka/Azure_VM_setup_and_Network_Configuration"> Azure VM Setup and Network Configuration </a>
- <a href="https://github.com/a-rashid-saaka/Active_directory_deployment_and_setup"> Active Directory Deployment and Setup </a>

<h2> Objective</h2>

<h4>Domain User Account Creation</h4>

-  Create multiple domain users using a PowerShell script to populate our domain.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services
- Powershell

<h2>Operating Systems Used </h2>

- Windows (Windows Server 2019 Datacenter)
- Windows (Windows 10 Pro)


<h1>Domain User Account Creation</h1>

<h3>&#9312; Execute PowerShell script</h3>
<p>We will use a PowerShell script to create domain user accounts in our Active Directory Domain. 
</p>

- Login to VM1-DC with the credentials of S-Samuels or any admin user
- Open PowerShell as an administrator, copy and paste the script provided here, <a href="https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1"> script </a>, and run it.

  
  ![image](https://github.com/user-attachments/assets/36f34937-f848-405a-bf11-8e2ccbd54177)

   - <p><strong>Learn more about the Powershell script here. <a href="https://www.youtube.com/watch?v=MHsI8hJmggI&t=1623s">User Generation script </a> </strong></p> 

<br>
<br>

- Once the script finishes running you can verify the newly created user accounts in the Active Directory Users and Computers


![image](https://github.com/user-attachments/assets/95c38ad7-efcf-4876-a712-a06b391cb410)

<p><strong>NOTE: Just for this tutorial, make sure the password policy is changed inside the Group Policy Objects of the domain, to allow us to create user accounts without password restrictions</strong></p>

<h3>&#9313; Login as domain user </h3>

- Let’s log in as a domain user to verify the previous task's success.
- Please remember to note the password used in our script (USERPASSWORD).
 
  ![image](https://github.com/user-attachments/assets/3ad72ba3-83ba-4ec4-a3b1-a30c728066d7)

  This user should be able to log in since it's one of the generated user accounts
<br>
<br>


<h2> Conclusion </h2>

<p>In conclusion, the "Active Directory Domain User Generation" project optimizes our user management process. By utilizing a PowerShell script, we can efficiently create domain user accounts.</p>


  
  
