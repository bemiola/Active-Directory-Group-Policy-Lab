Lab 01: Downloading VMware Workstation Pro 26H1 for Windows
Objective
Obtain the VMware Workstation Pro installer for Windows from the official VMware/Broadcom download service. VMware Workstation Pro will be used to create and manage Windows Server 2022 and Windows 11 virtual machines for the Active Directory and Group Policy home lab.
Lab Environment
Component	Details
Host operating system	Windows 11
Virtualization software	VMware Workstation Pro 26H1 for Windows
Download provider	VMware / Broadcom
Planned guest operating systems	Windows Server 2022 and Windows 11
Installer filename	`VMware-Workstation-Full-26H1-25388281.exe`
Installer size shown in File Explorer	280,929 KB (approximately 274 MiB)
Step 1: Locate the official VMware Workstation product page
Open a web browser and navigate to the official VMware Workstation and Fusion product page.
Locate the Fusion and Workstation section describing desktop virtualization products.
Select DOWNLOAD NOW to proceed toward the official download service.
![VMware Fusion and Workstation product page](../screenshots/lab-03-vmware-workstation-download/01-vmware-official-product-page.png)
Figure 1: Official VMware Fusion and Workstation product page showing the Download Now option.
![VMware Workstation download entry point](../screenshots/lab-03-vmware-workstation-download/02-vmware-download-now.png)
Figure 2: Second capture of the VMware product page and its download button.
Step 2: Create a Broadcom account and select the Windows installer
Create a Broadcom account as required to access the download portal, and sign in.
Open the VMware Workstation Pro product downloads.
Review the available releases for Windows and Linux.
Select VMware Workstation Pro 26H1 for Windows because the lab host uses Windows 11.
Follow the portal's download prompts to obtain the Windows installer.
![Broadcom VMware Workstation Pro release selection](../screenshots/lab-03-vmware-workstation-download/03-broadcom-workstation-download-versions.png)
Figure 3: Broadcom download portal showing VMware Workstation Pro 26H1, 25H2, and 17.0 options for Windows and Linux.
Step 3: Verify that the installer was downloaded
Open Windows File Explorer and navigate to the folder containing the downloaded installer.
Locate `VMware-Workstation-Full-26H1-25388281.exe`.
Confirm that File Explorer identifies the file as an Application and displays its file size.
![Downloaded VMware Workstation Pro 26H1 installer](../screenshots/lab-03-vmware-workstation-download/04-vmware-26h1-installer-downloaded.png)
Figure 4: Windows File Explorer showing the VMware Workstation Pro 26H1 installer (280,929 KB).
Technical Explanation
VMware Workstation Pro is a desktop hypervisor that runs multiple virtual machines on a single host computer. Each VM can have its own virtual CPU, memory, storage, and network configuration. In this lab, VMware will host Windows Server 2022 for Active Directory services and Windows 11 for domain-client testing.
The Windows installer is appropriate for the Windows host; the Linux downloads shown in the portal are not needed for this setup. Downloading the `.exe` installer is distinct from installing VMware Workstation Pro or creating a VM.
Verification and Outcome
[x] Located the official VMware product download page.
[x] Created a Broadcom account to access the download portal (user-reported).
[x] Selected VMware Workstation Pro 26H1 for Windows.
[x] Located the downloaded Windows installer in File Explorer.
[ ] Installed VMware Workstation Pro (not yet documented).
[ ] Verified VMware launches successfully (not yet documented).
Outcome: The VMware Workstation Pro 26H1 Windows installer is available for the next stage of the lab. File integrity and installer execution have not yet been verified.
Next Step
Install VMware Workstation Pro, verify it launches, and then create the Windows Server 2022 and Windows 11 virtual machines. Document the installation wizard, any required reboot, and the VM hardware/network settings separately.
