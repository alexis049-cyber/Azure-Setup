<img width="884" alt="Screenshot 2025-01-23 at 7 59 52 PM" src="https://github.com/user-attachments/assets/14983237-8b1a-4703-8a5b-d5f0d3e188f9" />

<h1>Azure Virtual Machine Setup</h1>

This repository provides a guide to setting up the necessary resources in Azure for our project. The setup includes creating a Resource Group, a Windows 10 Virtual Machine (VM), and a Linux (Ubuntu) Virtual Machine within the same Virtual Network (VNet) and Subnet. These resources will form the foundation for further project work.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>Steps</h2>
<img width="774" height="664" alt="image" src="https://github.com/user-attachments/assets/b762e23d-9c1e-4681-832c-f541bc457bfa" />


**1. Access Azure Portal**
    - Open the [Azure](https://portal.azure.com/) Portal.

**2. Create a Resource Group**

- Navigate to Resource Groups.
- Select Create.
- Provide a Resource Group Name and select a region.
- Click Review + Create and then Create.

<img width="986" height="726" alt="image" src="https://github.com/user-attachments/assets/5dccebc7-3a5b-4d86-b8f2-5b328333e48f" />
<img width="1502" height="394" alt="image" src="https://github.com/user-attachments/assets/c00d38d8-d3ed-4377-a8d7-ee78c6c8a7b1" />


**3. Create a Windows 10 Virtual Machine**

- Navigate to Virtual Machines.
- Select Create > Virtual Machine.
- Provide the following details:
    - Resource Group: Select the Resource Group created earlier.
    - VM Name: Enter a name for your Windows 10 VM.
    - Image: Choose "Windows 10".
    - Authentication Type: Username/Password.
    - Allow Azure to create a new Virtual Network (VNet) and Subnet.
- Configure other settings as needed and click Review + Create and then Create.

<img width="1104" height="1006" alt="image" src="https://github.com/user-attachments/assets/033a51cf-fa88-4b37-8f8f-f455dc9b753a" />
<img width="1110" height="650" alt="image" src="https://github.com/user-attachments/assets/2b7f57c1-b030-4e77-ae0d-749664c6e751" />
<img width="1162" height="764" alt="image" src="https://github.com/user-attachments/assets/04c5689b-a4c7-4c1a-8e73-39c60e8eb99b" />


**4. Create a Linux (Ubuntu) Virtual Machine**

- Navigate to Virtual Machines.
- Select Create > Virtual Machine.
- Provide the following details:
    - Resource Group: Select the same Resource Group used for the Windows 10 VM.
    - VM Name: Enter a name for your Linux (Ubuntu) VM.
    - Image: Choose "Ubuntu Server".
    - Authentication Type: Username/Password.
    - Virtual Network: Select the previously created Virtual Network.
    - Subnet: Ensure it matches the Subnet of the Windows 10 VM.
- Configure other settings as needed and click Review + Create and then Create.

<img width="1180" height="1232" alt="image" src="https://github.com/user-attachments/assets/6ff2fedc-7977-4898-a513-e971bce87bff" />
<img width="1182" height="658" alt="image" src="https://github.com/user-attachments/assets/0a31889d-9c23-4e8a-bb52-546f1c1c3309" />
<img width="1236" height="722" alt="image" src="https://github.com/user-attachments/assets/2b547cce-dcaf-4417-bf9b-f601538e8497" />


**5. Verify Setup**
- Ensure both VMs are in the same Virtual Network and Subnet.




<h2>Purpose</h2>

The purpose of this repository is to create the essential Azure resources—Virtual Machines, Resource Group, and Virtual Network—required to begin our project. The setup ensures both VMs are in the same Virtual Network and Subnet for seamless communication.
