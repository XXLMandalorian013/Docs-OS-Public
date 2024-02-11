# Fedora Workstation Install and Configuration - Fedora Workstation

2024-01-27

## Objective:

1. Install and configure Fedora Workstation.

## Prerequisites/Notes:

1. This guide was done on a Hyper-V machine.
2. Knowledge of how to create a VM is required as it is not covered in this guide.
3. Btrfs is the default file system.
4. GNOME is the default GUI experience.

## Steps:

1. Select or let it time out to "Test…& Start this media". This is ideal to ensure there are no errors when booting.

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-1.png)

2. The machine will boot and display its various boot log outputs.

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-2.png)

3. Once at the desktop GUI, click "Install Fedora" to make it a permanently installed OS.

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-3.png)

4. Select your language.

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-4.png)

5. Under "System," click "Install Destination."

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-5.png)

6. If only one drive is allocated to this VM, only one will be displayed. Automatic storage configuration will be picked by default. Click "Done."

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-6.png)

7. Should your VM's VHD already have preserved partitions and not enough space, you will be prompted to delete some to make room.
   
![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-7-1.png)
   
   Preserve, delete, or shrink as you see fit and click "Reclaim space."

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-7-2.png)

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-7-1.png)

8. Now click "Begin Install", 

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-8-1.png)

   wait for it to finish installing,

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-8-2.png)

   and click "Finish" when done.

9. Shutdown the VM, remove the boot media, and let it boot up normally into Fedora Workstation by itself. Once at the OS, it will prompt for additional setup. That’s it!

![Alt text](https://github.com/XXLMandalorian013/Docs-OS-Public/blob/main/Fedora/Fedora%20Workstation%20Install%20and%20Configuration%20-%20Fedora%20Workstation/images/s-9.png)

## Links:

1. [Fedora Workstation download](https://fedoraproject.org/workstation/download)
2. [Fedora WS docs](https://docs.fedoraproject.org/en-US/workstation-docs/)

