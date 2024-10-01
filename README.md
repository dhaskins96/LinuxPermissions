<h1>Manage File Permissions With Linux Lab</h1>

 


<h2>Description</h2>
In this lab, I was tasked with managing file permissions within the /home/researcher2/projects directory for the researcher2 user, who is part of the research_team group. I examined the permissions of all files, including hidden ones, ensuring they aligned with the correct authorization. Where permissions were incorrect, I modified them to maintain proper security. Additionally, I reviewed and adjusted the permissions of the /home/researcher2/projects/drafts directory, removing any unauthorized access to ensure confidentiality.
<br />


<h2>Languages and Utilities Used</h2>

- Linux

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
List the contents and permissions of the projects directory:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check whether any hidden files exist in the projects directory: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check whether any files in the projects directory have write permissions for the owner type of other:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change the permissions of the file identified in the previous step so that the owner type of other doesn’t have write permissions:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The file project_m.txt is a restricted file and should not be readable or writable by the group or other; only the user should have these permissions on this file. List the contents and permissions of the current directory and check if the group has read or write permissions:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change permissions of the project_m.txt file so that the group doesn’t have read or write permissions.:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change the permissions of the file .project_x.txt so that both the user and the group can read, but not write to, the file: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> Check the permissions of the drafts directory:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove the execute permission for the group from the drafts directory:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Lab complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
