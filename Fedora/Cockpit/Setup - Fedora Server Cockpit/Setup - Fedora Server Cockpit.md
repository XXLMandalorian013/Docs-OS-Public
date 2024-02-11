# Setup - Fedora Server Cockpit

2024-01-27

## Objective:

1. View and administer server(s) remotely via the browsers with a GUI experience and or via the CMD line for an Over of the server, Logs, Storage, Networking, Accounts, Services, Software updates, and more!

## Prerequisites/Notes:

1. Root can't log into Cockpit.
	
2. When logging in, user accounts should ideally be in the "wheel" group to use all aspects of Cockpit.
	
3. To manage multiple servers via cockpit, it's ideal to set the hostname of your servers to your liking if you have not done so already since creating.
	
## Steps:

1. After your server is installed/configured and you are ready to log into your server, you can see the prompt to access
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Setup%20-%20Fedora%20Server%20Cockpit/images/s1.png)	
	
2. Type in the user account and password that already exists on the device.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Setup%20-%20Fedora%20Server%20Cockpit/images/s2.png)	
	
3. Once logged in, you will get a GUI of your server.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Setup%20-%20Fedora%20Server%20Cockpit/images/s3.png)	
	
4. You may notice the "Limited Access" notification at the top. If the user account you are logged in at has sudo access you can administer additional aspects of the server like software updates.
	
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Cockpit/Setup%20-%20Fedora%20Server%20Cockpit/images/s4.png)	
	
Simply click on the "Limited Access" button and provided your password once again to your user account with sudo access.

## Links:

1. [Fedora Cockpit -](https://cockpit-project.org/running.html#fedora)
	
2. [Additional Cockpit app -](https://cockpit-project.org/applications.html)

