📌 Prerequisites

1. Download VirtualBox (latest version recommended)
-  Windows Server 2025 ISO (from Microsoft Evaluation Center or licensed copy)
A host machine with at least:
- 8 GB RAM (16 GB recommended)
- 50 GB+ free disk space
- 64-bit processor with virtualization enabled (Intel VT-x / AMD-V)
  
2. Change System Settings Processor

- Click on Settings -> Motherboard -> Change Base Memory to 4096 MB or 4GB. 
- Click on Processor -> Change CPU's quantity to 4 CPU's.

3. Change Network Settings

- Click on Settings -> Network
- If you want a private lab network pick -> Enable Network Adapter -> Bridged Adapter (This will allow your VM to communicate with other VM's on the same network) 
- If you want a Internet Access network -> Enable Network Adapter -> Adapter 1 -> NAT (This will allow DHCP to boot up for your virtual machine connecting it to the internet) Adapter 2 -> Host Only Adapter 

4. Boot up Windows Server 2025

- Select the Language and Time
- Choose Windows Server 2025
- Accept the license terms and choose virtual disk
- Set up the administrator account password

5. Create 

README.md → this guide
