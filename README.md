# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit

Reg.No:212223040106

Name:Madeswaran M

## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:

### **Step 1: Install  VM ware Worskstation**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualMAchine Ware Workstation website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VMware to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version




## OUTPUT:

### VIRTUAL MACHINE :

<img width="1919" height="1007" alt="Screenshot 2025-08-14 141819" src="https://github.com/user-attachments/assets/ad9f2c48-cb80-42cb-b56a-aeab80dfb50e" />

### KALI LINUX:


<img width="1919" height="989" alt="Screenshot 2025-08-14 141759" src="https://github.com/user-attachments/assets/02f11f97-fbdc-4404-a269-8c886760158b" />


### SLEUTH KIT:

<img width="937" height="105" alt="Screenshot 2025-08-14 142740" src="https://github.com/user-attachments/assets/5b9d3cc9-fb05-48de-8e85-10796e345089" />


# SLEUTH KIT ON KALI 

<img width="698" height="614" alt="Screenshot 2025-08-14 142730" src="https://github.com/user-attachments/assets/c0f7b278-0007-40f5-bb94-14cec1b78e0e" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
