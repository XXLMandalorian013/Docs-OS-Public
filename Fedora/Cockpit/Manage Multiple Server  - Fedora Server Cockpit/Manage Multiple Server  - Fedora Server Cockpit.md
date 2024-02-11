# Manage Multiple Server  - Fedora Server Cockpit

2024-01-27

## Objective:

1. Manage mutiple servers via  GUI and cli from a single pane of glass.

## Prerequisites/Notes:

1. Root can't log into Cockpit.
	
2. When logging in user accounts should ideally be in the "wheel" group to use all aspects of Cockpit.
	
3. To manage multiple servers via cockpit, it's ideal to set the hostname of your servers to your liking if you have not done so already since creating.
	
## Steps:

1. Log back into one of your cockpit enabled servers.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s1.png)	

2. To add additional hosts to this cockpit instance, simply "expand the carrot in the top left" and click "Add new host".
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s2.png)	
	
3. Define the hosts name, and a user account that already exists on the server. Note, root can’t be used.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s3.png)	
	
4. You will now see a SHA265 key and a way to view the device you are trying to add to cockpit SHA265 key.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s4.png)	
	
5. Log into and type out the ssh-keyscan -t… provided by cockpit and ensure what is displayed on your server matches the SHA265 in the picture above.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s5.png)	
	
6. If it does click "Accept and Continue".
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s6.png)	
	
7. Provide your password again and click "Log In".
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s7.png)	
	
8. You now have multiple server to manage in Cockpit!
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Manage%20Multiple%20Server%20%20-%20Fedora%20Server%20Cockpit/images/s8.png)	

Links:

1. [Fedora Cockpit -](https://cockpit-project.org/running.html#fedora)
	
2. [Additional Cockpit app -](https://cockpit-project.org/applications.html)


