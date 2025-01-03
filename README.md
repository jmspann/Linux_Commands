# Basic Linux Commands
Lab utilizing basic Linux commands for navigation, file and authorization management, and filtering.
<h1>Basic Linux Commands</h1>

<h2>Description</h2>
This lab utilizes basic Linux commands for a number of tasks a cybersecurity analyst may perform including: installing Suricata and tcpdump, generating outputs, navigating through directories, and filtering content using grep.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux Command-Line</b> 

<h2>Environments Used </h2>

- <b>KALI LINUX</b>
- <b>Linux Bash Shell</b>

<h2>Program Walk-Through:</h2>

<h3>Install APTs</h3>

<p align="center">
Check that the APT is installed using the <em><strong>apt</strong></em> command: <br/>
<img src="https://i.imgur.com/hweSG31.png" height="100%" width="100%" alt="Installation Steps"/>
<br />
<br />
Install tcpdump using the <em><strong>sudo</strong></em> command:  <br/>
<img src="https://i.imgur.com/PQwNPRE.png" height="100%" width="100%" alt="Installation Steps"/>
<br />
<br />
Verify tcpdump was installed successfully by typing <em><strong>apt list --installed</strong></em> in the command prompt: <br/>
<img src="https://i.imgur.com/1ub4E6G.png" height="100%" width="100%" alt="Installation Steps"/>
<br />
<br />
Install Suricata using the <em><strong>sudo</strong></em> command:  <br/>
<img src="https://i.imgur.com/28kvYXT.png" height="100%" width="100%" alt="Installation Steps"/>
<br />
<br />
Verify Suricata was installed successfully by typing the same command from above: <br/>
<img src="https://i.imgur.com/AHEFxA0.png" height="100%" width="100%" alt="Installation Steps"/>
</p>
<br />
<br />

<h3>Generate Outputs</h3>

<p align="center">
Generate string outputs using the <em><strong>echo</strong></em> command:  <br/>
<img src="https://i.imgur.com/qtlhg6d.png" height="100%" width="100%" alt="Generate Outputs"/>
<br />
<br />
Now generate mathematical expressions using the <em><strong>expr</strong></em> command:  <br/>
<img src="https://i.imgur.com/l8hauds.png" height="100%" width="100%" alt="Generate Outputs"/>
</p>
<br />
<br />

<h3>Navigate Through Linux</h3>

<p align="center">
Print the current working directory and list the contents using the <em><strong>pwd</strong></em> and <em><strong>ls</strong></em> commands:  <br/>
<img src="https://i.imgur.com/zpAXUZo.png" height="100%" width="100%" alt="Linux Navigation"/>
<br />
<br />
Now change directories to "reports" and list its contents using the <em><strong>cd</strong></em> command:  <br/>
<img src="https://i.imgur.com/avNLmjH.png" height="100%" width="100%" alt="Linux Navigation"/>
<br />
<br />
Navigate to the "users" directory and list its contents. After listing the contents, open a file using the <em><strong>cat</strong></em> command:  <br/>
<img src="https://i.imgur.com/In4Xm05.png" height="100%" width="100%" alt="Linux Navigation"/>
<br />
<br />
Now navigate to the "logs" directory and display the first 10 lines of the file it contains using the <em><strong>head</strong></em> command:  <br/>
<img src="https://i.imgur.com/iiUqgIf.png" height="100%" width="100%" alt="Linux Navigation"/>
</p>
<br />
<br />

<h3>Filtering</h3>

<p align="center">
After navigating to the "logs" directory, filter the "server_logs.txt" file for any lines that contain the string "error" using the <em><strong>grep</strong></em> command:  <br/>
<img src="https://i.imgur.com/gc2xuOc.png" height="100%" width="100%" alt="Grep Filtering"/>
<br />
<br />
Now navigate to the "users" directory and filter only the files that contain the string "Q1" and "access" respectively using <em><strong>|</strong></em> and <em><strong>grep</strong></em>:  <br/>
<img src="https://i.imgur.com/kz7MI1C.png" height="100%" width="100%" alt="Grep Filtering"/>
<br />
<br />
Search  the "Q2_deleted_users.txt" file for the username "jhill". Afterawrds, search for the string "Human Resources" in the "Q4_added_users.txt" file:  <br/>
<img src="https://i.imgur.com/OwJS4wJ.png" height="100%" width="100%" alt="Grep Filtering"/>
</p>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
