# Blue Team


## Disclaimer

This game is for educational purposes only. Unauthorized use of the tools that are incorporated into the game is illegal. The story is fictitious.


### Introduction Level

Welcome to the Blue Team training! This challenge will teach you how to secure a system from reconnaissance to incident response.
Now, let's get into the story: Ivan learned a valuable lesson when his server was compromised due to his poor security practices. After calling you for help, he realized he needed to implement strong defenses to prevent future attacks. Now, it's your job to step into the shoes of the Blue Team to harden Ivan's server and ensure it is secure against similar pranks (or actual malicious actors). :)

###Level 1: Get Access 

Firstly, let's access the Kali Linux machine we will use for this training!
On your right, a window with a topology should appear, showing available machines and networks.

You will only have access to the client's machine.
To access the client machine, right-click it and then select console (deprecated).
Your login credentials for the client machine are:
Username: ivan
Password: mainpass
When you log in to the client machine, you should be able to open the terminal inside it.

### Level 2: Initial Assessment 

Ivan's server behaves suspiciously, and his access has been locked out. Your mission is to investigate the server's current state and identify potential vulnerabilities. :)
He told us that his server IP is: 10.1.26.9
To progress further, execute a command that provides all open ports, running services, and potential entry points on Ivan's server.

### Level 3: Regaining Access 

The Nmap scan revealed a few troublesome vulnerabilities on Ivan's server. Before we can mitigate them, we need to log into it.
Fortunately, Ivan has made himself a backup user on his server! He stores a file with the backup user's credentials in his Home directory. (which is a bad practice)
Find the file with credentials and use them to log into Ivan's server.

### Level 4: Vulnerability Mitigation 

We are in! Now, let's mitigate the vulnerabilities on Ivan's server.
Earlier, the Nmap scan showed two significant vulnerabilities:
Anonymous access is enabled on the FTP server.
Root login is allowed on the SSH server.
Edit the configuration files and restart the services to apply changes.

### Level 5: System Search 

Now, search the system for malicious files left by the attacker.
Look for scripts with a .sh extension. If you find any, delete them!

### Level 6: Changing Password 

We are almost done securing Ivan’s compromised server. Now, we need to change the password for the ivan user.
Since we don't know the current password, execute the command with privileges.

### Level 7: Finish Line
 
Good job! This challenge highlights the defensive measures necessary to secure a compromised server. :)
I hope you learned a few things along the way! This training covered:
Assessing and documenting vulnerabilities
Regaining control of a compromised account
Hardening services like FTP and SSH
The importance of secure passwords


Estimated Duration: 25 minutes
