# **Configure Your Virtual Machine and GitHub**

## **1. Understanding Virtual Machines (VMs)**
Virtual Machines allow you to run multiple operating systems on a single physical machine. There are two types of VM usage:
- **Online VMs** – No installation needed but requires an internet connection (e.g., [DistroSea](https://distrosea.com/)).
- **Offline VMs** – Installed on your computer, allowing permanent storage and full control.

### **Popular Virtual Machine Software**
- **VMware Player**: [Download Here](https://www.techspot.com/downloads/1969-vmware-player.html)
- **VirtualBox**: [Download Here](https://www.virtualbox.org/)
- **Oracle VM**: [Download Here](https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html)

---

## **2. Setting Up a Virtual Machine (VM)**
### **Step 1: Download and Install a Virtual Machine Software**
1. Choose one of the above virtual machine software and download it.
2. Run the installer and follow the setup instructions.
3. Accept the license agreement and proceed with the installation.
4. Select the default or custom installation options as per your requirement.
5. Wait for the installation to complete and restart your computer if necessary.

### **Step 2: Download One of the Below ISO Files**
You need an ISO file to install an operating system on your VM.
- **Ubuntu**: [Download Here](https://ubuntu.com/download)
- **Kali Linux**: [Download Here](https://ccm.net/downloads/operating-systems/6917-kali-linux-iso/?n=&version=iso)
- **Windows 7**: [Download Here](https://archive.org/download/win-7-pro-32-64-iso/64-bit/)

### **Step 3: Create a New Virtual Machine**
1. Open your VM software (VMware, VirtualBox, or Oracle VM VirtualBox).
2. Click on **New** to create a new virtual machine.
3. Provide a name for your VM (e.g., Ubuntu VM, Kali VM, Windows VM).
4. Choose the type of operating system you are installing (Linux/Windows).
5. Assign **RAM (Memory)**:
   - Linux (Ubuntu/Kali): Minimum **2GB** (Recommended: **4GB**)
   - Windows 7: Minimum **4GB** (Recommended: **6GB+**)
6. Create a **virtual hard disk**:
   - Select **Create a Virtual Hard Disk Now**.
   - Choose the disk file type (**VDI, VMDK, or VHD**).
   - Choose **Dynamically Allocated** (adjusts as needed) or **Fixed Size** (better performance but takes more space).
   - Allocate at least **20GB** of storage.
7. Attach the **ISO file** to the VM:
   - Click **Settings** > **Storage**.
   - Click the **Empty disk icon**.
   - Select **Choose a disk file** and browse to your downloaded ISO.
8. Configure additional settings:
   - Enable **EFI boot** for modern OS compatibility.
   - Adjust **Processor cores** to **2-4 cores** for better performance.
   - Enable **3D Acceleration** (if required).
9. Click **Start** to boot the VM and begin OS installation.
10. Follow the OS installation steps, such as:
    - Setting up language, time zone, and keyboard layout.
    - Creating a username and password.
    - Selecting disk partition options (use default settings for beginners).
    - Waiting for installation to complete and restarting the VM when prompted.

Now your Virtual Machine is ready to use! 🚀
