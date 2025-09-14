# PfSense-Setup
pfSense deployment for a home lab replicating enterprise security. Features include firewalling, VPN, VLAN segmentation, IDS/IPS, and policy-based routing to demonstrate practical network security design and administration skills.

🔧 Installation

  Step 1. Download pfSense:
  
    - Get the latest pfSense ISO from the official website:


    - Choose the appropriate architecture (AMD64/Netgate device):

  Step 2. Virtualized Install:

    - I will be using VirtualBox, so I had to download the ISO and create a VM.  I also added 3 Network interfaces, 1 for the WAN(10.0.2.3/8), 1 for the LAN(172.16.0.100-200/24) and 1 for the DMZ (192.168.1.1/8)

    - Allocate at least 2 vCPU, 2GB RAM, and 20GB disk for lab testing.
