# Lab 02: Downloading Windows 11 ISO

## Objective

Download the official Windows 11 64-bit ISO from Microsoft to prepare to deploy a Windows 11 virtual machine in VMware Workstation Pro.

The Windows 11 virtual machine will serve as a domain-joined workstation for testing Active Directory authentication, Group Policy Objects (GPOs), user permissions, and endpoint management.

## Technologies Used

| Component | Technology |
|---|---|
| Virtualization Platform | VMware Workstation Pro |
| Server Operating System | Windows Server 2022 |
| Client Operating System | Windows 11 |
| Installation Media | Windows 11 Multi-Edition ISO (x64) |
| Download Source | Microsoft Software Download |

## Step 1: Access the Microsoft Windows 11 Download Page

1. Open a web browser.
2. Navigate to the official [Microsoft Windows 11 Download Page](https://www.microsoft.com/en-us/software-download/windows11).
3. Locate the **Download Windows 11 Disk Image (ISO) for x64 devices** section.
4. From the dropdown menu, select **Windows 11 (multi-edition ISO for x64 devices)**.
5. Click **Confirm** to continue.

![Windows 11 ISO selection](../screenshots/03-windows11-iso-selection.png)

*Figure 1: Microsoft Windows 11 download page displaying the multi-edition ISO selection for x64 devices.*

## Step 2: Download the Windows 11 ISO

1. Select the appropriate language when prompted.
2. Confirm the language selection.
3. Locate the **64-bit Download** button.
4. Click the button to download the Windows 11 ISO.
5. Save the installation media to the Downloads folder.

![Windows 11 64-bit download](../screenshots/04-windows11-64bit-download.png)

*Figure 2: Microsoft download page displaying the Windows 11 Client Build 26300.9457 English 64-bit download option.*

## Step 3: Verify the Downloaded ISO

After downloading the installation media, I opened Windows File Explorer and located the Windows 11 ISO file in my Downloads folder.

**Downloaded ISO Details**

| Property | Value |
|---|---|
| Filename | `Windows11_Client_x64_en-us_26300_9457.iso` |
| Architecture | x64 (64-bit) |
| Language | English (United States) |
| Build | 26300.9457 |
| File Type | ISO Disc Image |
| File Size | 8,835,284 KB (approximately 8.43 GiB) |

![Downloaded Windows 11 ISO](../screenshots/05-windows11-iso-verification.png)

*Figure 3: Windows File Explorer showing the downloaded Windows 11 ISO installation media.*

## Technical Explanation

An ISO file contains the installation media required to deploy an operating system. VMware Workstation Pro can mount this file to a virtual machine's CD/DVD drive, allowing Windows 11 to be installed in a virtual environment.

The Windows 11 virtual machine will act as a domain client connected to the Windows Server 2022 domain controller.

This will allow hands-on practice with:

- Joining Windows workstations to an Active Directory domain.
- Authenticating users with domain credentials.
- Applying and testing Group Policy Objects.
- Managing users, security groups, and workstation permissions.
- Testing domain security configurations.
- Troubleshooting Group Policy application and authentication issues.

**Note:** Windows 11 Pro, Enterprise, or Education is required for traditional Active Directory domain joining. Windows 11 Home does not support this feature.

## Verification Results

The Windows 11 ISO was located in the Downloads folder, and its filename, file type, and size were verified using Windows File Explorer.

The screenshot confirms that the installation media is present. ISO integrity and boot functionality have not yet been tested.

## Outcome

Successfully obtained Windows 11 installation media for use as a virtual domain workstation in the Active Directory and Group Policy home lab.

## Next Steps

Configure virtual machines in VMware Workstation Pro, install Windows Server 2022 and Windows 11, and prepare the environment for Active Directory domain configuration.
