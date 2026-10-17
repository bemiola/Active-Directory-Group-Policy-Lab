# Lab 03: Downloading VMware Workstation Pro

## Objective

Download VMware Workstation Pro from the official VMware/Broadcom website to prepare for deploying and managing virtual machines in an Active Directory and Group Policy home lab.

VMware Workstation Pro will serve as the virtualization platform for running Windows Server 2022 and Windows 11 virtual machines on a single physical computer.

The virtual environment will provide hands-on experience with Windows Server administration, Active Directory Domain Services (AD DS), Group Policy management, network configuration, and PowerShell automation.

## Technologies Used

| Component | Technology |
|---|---|
| Virtualization Platform | VMware Workstation Pro 26H1 |
| Host Operating System | Windows 11 |
| Server Operating System | Windows Server 2022 |
| Client Operating System | Windows 11 |
| Software Provider | VMware by Broadcom |
| Installer Architecture | Windows x64 |
| Installation File Type | Windows Executable (.exe) |

## Step 1: Access the Official VMware Workstation Pro Website

1. Open a web browser.
2. Navigate to the official VMware desktop hypervisor product page.
3. Locate the **Fusion and Workstation** section.
4. Review the product information for VMware Workstation Pro.
5. Select **Download Now** to access the software download portal.

![VMware Workstation Pro product page](../screenshots/lab-03-vmware-workstation-download/01-vmware-product-page.png)

*Figure 1: Official VMware Fusion and Workstation product page displaying the Download Now option.*

## Step 2: Create a Broadcom Account

To access the VMware Workstation Pro installation files, I created a Broadcom account.

1. Follow the download link to the Broadcom Support Portal.
2. Select the account registration option.
3. Complete the required registration information.
4. Verify the account if prompted.
5. Sign in to the Broadcom Support Portal.
6. Navigate to the VMware software downloads section.

**Technical Explanation**

Broadcom provides access to VMware software downloads through its support portal. Creating an account allows users to authenticate and access available software installation packages.

## Step 3: Locate VMware Workstation Pro for Windows

After signing in to the Broadcom Support Portal, I navigated to the VMware Workstation Pro product downloads.

The portal displayed multiple versions of VMware Workstation Pro for Windows and Linux, including:

- VMware Workstation Pro 26H1 for Windows
- VMware Workstation Pro 26H1 for Linux
- VMware Workstation Pro 25H2 for Windows
- VMware Workstation Pro 25H2 for Linux
- VMware Workstation Pro 17.0 for Windows
- VMware Workstation Pro 17.0 for Linux

Because my host computer runs Windows 11, I selected **VMware Workstation Pro 26H1 for Windows**.

![Broadcom VMware Workstation Pro downloads](../screenshots/lab-03-vmware-workstation-download/03-broadcom-workstation-versions.png)

*Figure 2: Broadcom Support Portal displaying the available VMware Workstation Pro versions for Windows and Linux.*

## Step 4: Download VMware Workstation Pro 26H1

1. Select **VMware Workstation Pro 26H1 for Windows** from the available products.
2. Navigate to the applicable software download package.
3. Select the Windows installer.
4. Initiate the download.
5. Save the installation file to the Downloads folder.

The downloaded installer was:

`VMware-Workstation-Full-26H1-25388281.exe`

## Step 5: Verify the Downloaded Installer

After downloading VMware Workstation Pro, I opened Windows File Explorer and located the installation file in my Downloads folder.

**Downloaded Installer Details**

| Property | Value |
|---|---|
| Filename | `VMware-Workstation-Full-26H1-25388281.exe` |
| Software | VMware Workstation Pro |
| Version | 26H1 |
| Build | 25388281 |
| Platform | Windows |
| File Type | Application (.exe) |
| File Size | 280,929 KB (approximately 274 MiB) |
| Date Shown | October 16, 2026 |

![VMware Workstation Pro installer](../screenshots/lab-03-vmware-workstation-download/04-vmware-installer-downloaded.png)

*Figure 3: Windows File Explorer displaying the downloaded VMware Workstation Pro 26H1 installer.*

## Technical Explanation

VMware Workstation Pro is a Type 2 hypervisor that enables multiple operating systems to run as virtual machines on a single physical host.

Each virtual machine operates with its own virtualized hardware resources, including:

- Virtual processors (vCPUs)
- Random Access Memory (RAM)
- Virtual hard disks
- Virtual network adapters
- Virtual CD/DVD drives

For this home lab, VMware Workstation Pro will be used to create and manage two primary virtual machines:

**Windows Server 2022**

The server will be configured to provide Active Directory Domain Services, DNS, and Group Policy management.

**Windows 11**

The client workstation will be joined to the Active Directory domain to test domain authentication, user permissions, and Group Policy configurations.

Using virtualization allows enterprise administration tasks to be practiced without deploying multiple physical computers.

## Verification Results

Confirmed that the VMware Workstation Pro 26H1 Windows installer was present in the Downloads folder.

The filename, file type, and file size were verified using Windows File Explorer.

The installer is available for the next stage of the lab. Installation and successful application launch have not yet been verified.

## Outcome

Successfully obtained VMware Workstation Pro 26H1 for Windows from the Broadcom software download portal.

The downloaded installer will be used to prepare the virtualization environment for deploying Windows Server 2022 and Windows 11 virtual machines.

## Skills Demonstrated

- Virtualization environment preparation
- Hypervisor software identification and acquisition
- Software download and installation media management
- Windows host environment preparation
- Enterprise IT infrastructure planning

## Next Steps

Install VMware Workstation Pro 26H1 on the Windows 11 host computer.

After installation, configure the virtualization environment and begin creating the Windows Server 2022 virtual machine for the Active Directory and Group Policy home lab.
