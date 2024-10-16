# Task of the Day: Deploying a Windows VM and Connecting via RDP

### Step-by-Step Guide:

1. **Login to Azure Portal**  
   Sign in at the [Azure Portal](https://portal.azure.com).

2. **Create a Virtual Machine (VM)**  
   - Search "Virtual Machines" and click **Create**.  
   - Select **Windows Server 2019 Datacenter** (or preferred version).  
   - Set basic settings:
     - Choose a **Resource Group** (or create one).
     - Name your VM and select a **Region**.
     - Select VM **Size** (e.g., Standard D2s_v3).
     - Set **Admin Username** and **Password**.

3. **Enable RDP (Port 3389)**  
   - Ensure port **3389** is selected under **Inbound Ports** for RDP access.

4. **Configure Networking**  
   - Attach the VM to a **Virtual Network (VNet)** or create one.
   - Ensure **Public IP** is enabled for remote access.

5. **Review and Create**  
   - Review settings and click **Create**.
   - Wait for the deployment to complete.

6. **Connect to the VM**  
   - Once deployed, go to **Virtual Machines**, select your VM, and click **Connect > RDP**.
   - Download the RDP file and open it.
   - Enter the **Username** and **Password** to connect.

7. **Access Your VM**  
   - You are now connected via RDP and can manage the Windows VM.
