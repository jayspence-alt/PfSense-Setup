# PfSense-Setup
pfSense deployment for a home lab replicating enterprise security. Features include firewalling, VPN, VLAN segmentation, IDS/IPS, and policy-based routing to demonstrate practical network security design and administration skills.

🔧 Installation

  Step 1. Download pfSense:
  
    - Get the latest pfSense ISO from the official website:

<img width="627" height="492" alt="Screenshot_68" src="https://github.com/user-attachments/assets/7be94a04-130a-4eb5-a4d7-79556e8f6dcc" />


    - Choose the appropriate architecture (AMD64/Netgate device):

<img width="1123" height="625" alt="Screenshot_69" src="https://github.com/user-attachments/assets/a7f955a0-7892-4ff5-90ed-c01d3ec6ca22" />


  Step 2. Virtualized Install:

    - I will be using VirtualBox, so I had to download the ISO and create a VM.  I also added 3 Network interfaces, 1 for the WAN(10.0.2.3/8), 1 for the LAN(172.16.0.100-200/24) and 1 for the DMZ (192.168.1.1/8).

  <img width="769" height="478" alt="Screenshot_47" src="https://github.com/user-attachments/assets/828ee9ff-77e8-4ca2-b950-98c6d3f0b6b4" />
  <img width="770" height="479" alt="Screenshot_48" src="https://github.com/user-attachments/assets/c2abef1a-e3ed-4954-9599-0f2dc8cc7503" />
  <img width="770" height="482" alt="Screenshot_70" src="https://github.com/user-attachments/assets/52a16b7e-62cc-4d57-a847-35e83e8e4187" />

    - Allocate at least 2 vCPU, 2GB RAM, and 20GB disk for lab testing. - This has been completed.

  Step 3. Assign Interfaces:

    - Configure WAN, LAN and DMZ interfaces during setup.

  <img width="1037" height="613" alt="Screenshot_50" src="https://github.com/user-attachments/assets/9e8e5507-2af2-47b2-af44-092343c95c4d" />
  <img width="751" height="425" alt="Screenshot_51" src="https://github.com/user-attachments/assets/e9312941-2e90-4f8c-af1c-17a1c0c37771" />
  <img width="752" height="425" alt="Screenshot_52" src="https://github.com/user-attachments/assets/76906a13-d8a4-4b84-89af-d0c0c1dd1419" />
  <img width="742" height="421" alt="Screenshot_53" src="https://github.com/user-attachments/assets/38638fb4-8990-4b24-a9dc-a55e1a1a55fe" />
  <img width="771" height="432" alt="Screenshot_54" src="https://github.com/user-attachments/assets/9a0585b9-4ac8-4984-8f49-e5fe31579b47" />

  Step 4. Initial Web Setup:
  
    - Access the pfSense web GUI at https://172.16.0.3.

  <img width="1038" height="785" alt="Screenshot_62" src="https://github.com/user-attachments/assets/48bbd024-89f8-466d-988b-6ef2a239d83f" />
  

    - Login: admin / pfsense.

  <img width="1063" height="794" alt="Screenshot_63" src="https://github.com/user-attachments/assets/a4b4b5ae-b814-45c1-a651-c807265eb496" />

    - Complete the setup wizard to configure hostname, domain, DNS, and WAN.

  <img width="1064" height="793" alt="Screenshot_64" src="https://github.com/user-attachments/assets/1ac8ecb8-1428-4efd-99b5-5f4bbf4316a6" />

  Step 5: Update System:

    - Navigate to System > Update and apply all security patches.

<img width="1077" height="801" alt="Screenshot_71" src="https://github.com/user-attachments/assets/ce4e0164-5293-40f2-87b6-283f5cc7de0b" />
<img width="1060" height="784" alt="Screenshot_72" src="https://github.com/user-attachments/assets/606a154c-91ac-4101-9343-fd66706297e8" />


    

