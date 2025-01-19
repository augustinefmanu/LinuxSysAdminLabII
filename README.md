<h1>Linux SysAdmin Fundamentals Lab II</h1>

<h2>Languages and Utilities Used</h2>

- <b>Ubuntu Linux</b>
- <b>Bash</b>
- <b>Command Line</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Description</h2>

Your senior administrator has asked you to audit the strength of users' passwords by using the john program and document any passwords that you find.

 <br />
 
<h2>Lab walk-through</h2>

<p align="center">
Copying shadow password file: <br/>
<img src="https://i.imgur.com/EOaP3cs.png" height="80%" width="80%" alt="Copying shadow file"/>
<br />
<br />
<p align="center">
Editing password file leaving only users of the system: <br/>
<img src="https://i.imgur.com/RAKpJJi.png" height="80%" width="80%" alt="Editing Shadow file"/>
<img src="https://i.imgur.com/22nOInc.png" height="80%" width="80%" alt=""/>
<br />
<br />
<p align="center">
Running shadow file through password cracker: <br/>
<img src="https://i.imgur.com/E4vUAe5.png" height="80%" width="80%" alt="Cracking password"/>
<img src="https://i.imgur.com/5pfFUeD.png" height="80%" width="80%" alt="Cracking password"/>
<br />
<br />

<h2>Description</h2>

The next steps provided by your senior administrator have to do with locking access to the compromised system, including sudo access. You are tasked with editing the sudoers file to remove sudo access.

 <br />
 
<h2>Lab walk-through</h2>

<p align="center">
Checking sudo access of users with weak passwords: <br/>
<img src="https://i.imgur.com/PggkFNJ.png" height="80%" width="80%" alt="Checking sudo access"/>
<br />
<br />
<p align="center">
Removing sudo access from users in the sudoers file: <br/>
<img src="https://i.imgur.com/OEMTu2O.png" height="80%" width="80%" alt="Removing sudo access"/>
<img src="https://i.imgur.com/MqXAGCa.png" height="80%" width="80%" alt="Removing sudo access"/>
<br />
<br />
Removing less access from users in the sudoers file: <br/>
<img src="https://i.imgur.com/MqXAGCa.png" height="80%" width="80%" alt="Removing less access"/>
<br />
<br />
<p align="center">
Confirming changes to sudoers file: <br/>
<img src="https://i.imgur.com/zC6YiY9.png" height="80%" width="80%" alt="Confirming changes"/>
<img src="https://i.imgur.com/COWsIh4.png" height="80%" width="80%" alt="Confirming changes"/>
<img src="https://i.imgur.com/1SNZRyS.png" height="80%" width="80%" alt="Confirming changes"/>
<br />
<br />

<h2>Description</h2>

Your senior systems administrator has asked you to audit these groups and remove both unauthorized users as well as suspicious groups.
To complete these tasks, your senior administrator has asked that you do the following:
Check every user's UID and GID.
Make sure that only the sysadmin account is in the sudoers group.
If you find a user that is part of the sudoers group, remove them from that group and document your findings.
Remove any users from the system that should not be there.
Verify that all non-admin users are part of the group developers. If the developers group doesn't exist, create it and add the users. We can use this group later to configure file-sharing among these users.
The users adam, billy, sally, and max should only be members of the developers group and their own ("primary") groups. If you find any other groups, document the group and remove it.

<h2>Lab walk-through</h2>

<p align="center">
Checking IDs for every user on the system: <br/>
<img src="https://i.imgur.com/Xar9Dua.png" height="80%" width="80%" alt="Checking userID"/>
<br />
<br />
<p align="center">
Checking groups users belong to on the system: <br/>
<img src="https://i.imgur.com/48pQP6r.png" height="80%" width="80%" alt="Checking groups"/>
<br />
<br />
<p align="center">
Removing Jack from sudo group: <br/>
<img src="https://i.imgur.com/NfFVGA1.png" height="80%" width="80%" alt=""/>
<br />
<br />
<p align="center">
Removing users and groups that should not be on the system: <br/>
<img src="https://i.imgur.com/JUCOsSw.png" height="80%" width="80%" alt="Removing users and groups"/>
<br />
<br />
<p align="center">
Adding users to appropriate group: <br/>
<img src="https://i.imgur.com/7MbeNee.png" height="80%" width="80%" alt="Adding users to group"/>
<br />
<br />
