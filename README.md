# Active Acoustics Strategic Initiative (AA-SI) Windows Virtual Machine

## About
The AA-SI has access to a Windows Virtual Machine (WindowsVM) for processing and analyzing data in the Windows environment. These instructions are for users to:
- Request a WindowsVM
- Setup the WindowsVM
- Install software </br>

As of summer 2026, we are using the passive acoustics monitoring (PAM) WindowsVM. At some time, hopefully in the near future, NOAA Fisheries OCIO will provide a VM and we will update this site. Until that time, we will provide instructions for the PAM VM. 

### Request a Windows VM
We are using a Windows VM that was created by Daniel Woodrich (daniel.woodrich@noaa.gov) for the PAM-SI. The PAM-SI is graciously allowing the AA-SI to use this VM. The PAM Windows VM is set up for the AA-SI, especially for use with Echoview with a cloud license and for accessing the AA-SI Google storage bucket. For this reason, we request that modifications be reserved for the Fisheries VM. </br>

1. The [PAM site](https://nmfs-ost.github.io/PAM-Cloud/content/PAM.ww.html) provides instructions on how to request, setup, and work with the PAM Windows VMs.
2. Click on the "submit a new issue here" link in [What are PAM Workstations](https://nmfs-ost.github.io/PAM-Cloud/content/PAM.ww.html#what-are-pam-windows-workstations) to request a VM.
3. **TBD**: I don't remember this process, but I ended up with a VM instance.
4. After requesting the VM, you will get a VM Instance, which you will use to logon and access the VMs.
   1. Access the [VM Instance](https://console.cloud.google.com/compute/instances?project=ggn-nmfs-pamdata-prod-1&pli=1&pageState=(%22instances%22:(%22p%22:1)))
   2. Find your name under the "Name" column, and click on the three vertical dots to the right and in the same row as your name.
   3. Click on "Start/Resume" and a message will appear to let you know that you are accruing charges. Click "Start".
   4. Starting the VM can take some time...
   5. When you see the message "VM instance started", you can access the VM via the next set of instructions.

### Access the Windows VM
1. When you have access to a VM, access the VM using the instructions in: [Access and Connection Instructions](https://nmfs-ost.github.io/PAM-Cloud/content/PAM.ww.html#access-and-connection-instructions).
   1. Use the "recommended IAP Desktop" option to access the VM.
   2. Install and setup the IAP Remote Desktop Connection according to the instructions.
3. After you have installed the IAP remote desktop connection, you can access the IAP app by typing IAP in the windows search box in your start menu.
   1. For easier access, you can add the IAP icon <img src="./images/IAP_icon.png" width="25" height="25"> to your taskbar.
5. The IAP Desktop application will open with a list of users on the left and a blank panel on the right.
   1. Find your username in the list
   2. Right-click on your username and select "Connect as User"
   3. The username is pam_user, and there is no password (i.e., leave it blank)
   4. If it asks for your password again, just click "OK".
7. It can take several tries to get the VM operational. If something happens, go back to IAP Desktop and try again, or sometimes it's necessary to stop the VM instance and start from the beginning.

## For new repositories in nmfs-ost organization
2) Add [topics](https://docs.github.com/en/enterprise-cloud@latest/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) to help users find repositories.

# Disclaimer
This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
