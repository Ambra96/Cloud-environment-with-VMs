# ☁️ Virtualized Cloud Infrastructure using VirtualBox

This project demonstrates how to create a complete **Cloud Infrastructure** lab environment using **Oracle VirtualBox**. The setup includes a Windows Server 2019 domain controller, a Windows 10 Pro workstation, and a TrueNAS Core storage server — all running as virtual machines (VMs). This virtual cloud environment is ideal for development, training, and proof-of-concept deployments.

---

## 📘 Project Overview

The goal of this project is to build a simulated enterprise IT environment that includes:

- **Windows Server 2019**  
  - Active Directory Domain Services  
  - DNS Server  
  - User & Group Management  
  - Group Policy Configuration  

- **Windows 10 Pro**  
  - Domain Client  
  - Connected to the domain  
  - Applies Group Policy (e.g., wallpaper, time sync)

- **TrueNAS Core**  
  - Storage Pool & Datasets  
  - SMB Share Configuration  
  - Joined to the Domain  
  - Secure file sharing with domain-level permissions

---

## 🧰 Technologies Used

- [VirtualBox](https://www.virtualbox.org/) – VM virtualization platform  
- [Windows Server 2019](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019) – Domain and service management  
- [Windows 10 Pro](https://www.microsoft.com/software-download/windows10) – End-user workstation  
- [TrueNAS Core](https://www.truenas.com/download-truenas-core/) – Open-source NAS (storage) solution

---

## 🗂 Files Included

- `Cloud_VB.pdf`: Full implementation guide with step-by-step setup instructions (in Greek)
- (Optional): Screenshots or VM config files (you can upload them here)

---

## 🚀 Setup Instructions (Summary)

1. **Install VirtualBox** on a host machine.
2. **Create three virtual machines**:
   - Windows Server 2019
   - Windows 10 Pro
   - TrueNAS Core
3. **Set up networking**:
   - Use **Internal Network** for private communication between VMs
   - Optionally, add **NAT** for internet access
4. **Configure Active Directory & DNS** on Windows Server
5. **Join the Windows 10 machine to the domain**
6. **Create a shared folder via TrueNAS**, configure SMB share, and join it to the domain
7. **Apply group policies** (e.g., time sync, shared wallpaper)
8. **Test domain login & access shared files**

---

## 🎯 Project Objectives

- Simulate an enterprise IT cloud environment
- Practice AD, DNS, GPO, and SMB file sharing
- Demonstrate virtualized storage and authentication integration
- Enhance networking and system administration skills

---

## 💡 Benefits

- **Scalable**: Can expand with more clients or services
- **Isolated**: Does not affect the host system
- **Educational**: Excellent for IT students and system administrators-in-training

---

## 📝 Authors

- **Ambra Nastini**
- **Evangelos Mileounis**

---

## 📄 License

This project is open for educational and non-commercial use.

