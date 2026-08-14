<div align="center">
  
# Cybersecurity Lab Environment Setup
## networkwalks-B082-week1-Cybersecurity-lab-setup
Cyber Security Lab Setup
</div>

---



## 📌 Project Overview
This project aims at building a controlled safe environment for cyber security testing, penetration testing and other learning practices. The lab is constructed using VirtualBox and Kali Linux(2026 version).

This lab is using NAT network and the private Virtual Network used here makes sure that more than one machine can be handled through it and a network of machines of different types can be created.

This lab can be used to practice:
* Security Lab
* Pentesting
* Linux
* SQL Injections
* XSS
* Networking and so on

---

## 🎯 Objectives

The main objectives of the project are to:
* Install and setup VirtualBox.
* Import Kali Linux as virtual machine.
* Create a private NAT Network, check connectivity.
* Assign and verify Network, IP address, DNS.
* Take a clean Snapshot of VM for future recovery.
* Document the full setup process.

---

## 🛡️ Purpose of the Lab

This lab is capable of providing controlled isolated environment for Cyber Security practice and learning.
This can be used for:
* Web security testing
* Penetration testing
* Exploitation practice
* Vulnerability assessment
* Port scanning
* Reconnaissance
* Experiments

Note: This lab should be used to experiment on authorized & permitted practices.
---


## 🖥️Lab Configuration

|  Component | Configuration |
| :--- | :--- |
| Host OS | Windows 11 |
| Host RAM | 8 GB |
| Processor | Intel Core i3 |
| Hypervisor | Oracle VirtualBox 7.2 |
| Security OS | Kali Linux 2026.2 |
| Kali RAM | 2048 MB |
| Virtual Network | NAT Network |
| Network Address | 10.0.0.0/24 |
| Kali Linux IP | 10.0.0.2/24 |
| Network Mask | 24 |
| Gateway | 10.0.0.1 |
| DNS Server | 8.8.8.8 |
| Future VM Range | 10.0.0.3–10.0.0.99 |

---

## ⚙️ Tools & Resources

* **7-Zip:** https://7-zip.org/download.html
* **VirtualBox:** https://virtualbox.org/wiki/Downloads
* **Kali Linux:** https://kali.org/get-kali

---

# 🪜Procedures:
## Step 1. Download & Install 7-Zip
Downloaded and Installed 7-Zip to extract the required zip files resulting in executable normal files.

<img width="1204" height="412" alt="image" src="https://github.com/user-attachments/assets/85f39a3c-e383-4a28-9c33-91fb02fbab66" />

  
---
  

## Step 2. Download & Install VirtualBox

<img width="817" height="438" alt="Screenshot 2026-08-12 182425" src="https://github.com/user-attachments/assets/46868a7b-044d-4e20-a79a-3ffe573e1301" />

<img width="1858" height="833" alt="Screenshot 2026-08-12 182550" src="https://github.com/user-attachments/assets/6a7f24fc-a6e7-4118-8de9-b1edebf50439" />



---



## Step 3. Create the NAT Network

So, now after opening the VirtualBox this interphase is seen. Initially if the Network option is not found inside tool or in side bar, then going in "Expert Mode" will solve it and all the advanced options will appear.

<img width="1920" height="1080" alt="Screenshot 2026-08-12 223416" src="https://github.com/user-attachments/assets/24cef3ff-300f-43ea-8351-dae1cf54f414" /> 

<img width="1026" height="376" alt="image" src="https://github.com/user-attachments/assets/28b73c82-2fae-4c52-9365-f6c0fa6e389b" />

<img width="1920" height="1080" alt="Screenshot 2026-08-12 232041" src="https://github.com/user-attachments/assets/7c101ae8-6a8e-4b1b-9299-95d05adc7403" />




---

## Step 4. Import Kali Linux

From the Kali linux official website, the software has to be downloaded and installed first.

* Website ➡️ Virtual Machines ➡️ VirtualBox ➡️ Download

A zip file is downloaded. Now 7-zip application is used to extract the files from the zip file into a normal accessible file.

Next, Kali linux will be added to the VirtualBox.

* VirtualBox ➡️ Machine ➡️ Open ➡️ a Dialog box popped ➡️ search the location path of the Kali Linux Folder ➡️ Select the Blue icon Kali Linux VBox file

Thus Kali Linux is added to the Virtual Box. Now it can be started using the Green Start button.

After adding Kali to The virtualBox, the NAT Network is added to the settings (The one created earlier)
* Settings ➡️ Dialog Box ➡️ Attached to ➡️ NAT Network ➡️ OK


<img width="1081" height="635" alt="Screenshot 2026-08-12 182905" src="https://github.com/user-attachments/assets/1af7b424-c072-4485-8e9c-0dee4e79dfef" />

<img width="1554" height="503" alt="image (1)" src="https://github.com/user-attachments/assets/6acfc825-7570-4c13-9bfa-52e8a475e550" />

<img width="970" height="354" alt="fgdd" src="https://github.com/user-attachments/assets/e5fea181-10cf-4b97-a62d-5ac3378e0fee" />

<img width="628" height="373" alt="Screenshot 2026-08-14 003021" src="https://github.com/user-attachments/assets/3ecb65bf-95b0-4f7f-a39a-c188a5929471" />

<img width="1540" height="838" alt="Screenshot 2026-08-12 233154" src="https://github.com/user-attachments/assets/3629d8fa-5cbe-48d9-a5be-de931187fce5" />


---

## Step 5. Configure the Kali Linux Network

Open the Machine (kali Linux), the default Username and Password is kali. User is supposed to change the credentials if needed while working.
<img width="1600" height="1200" alt="WhatsApp Image 2026-08-14 at 1 42 45 AM" src="https://github.com/user-attachments/assets/3108da56-6893-4c9f-93ad-6ab03ce62b12" />



https://github.com/user-attachments/assets/eabeb261-f7c2-431b-a044-3323f31733e6

---

## Used Commands in terminal:
* ifconfig
* sudo ifconfig eth0 down
* sudo ifconfig eth0 up
* ping google.com

<img width="659" height="523" alt="image" src="https://github.com/user-attachments/assets/95757c4c-e791-427d-8c19-139dd1029a3f" />


---

## Step 6. Take a Clean Snapshot of the Virtual Machine
After the procedures, a VirtualBox snapshot was created.

Current State ➡️ Right click ➡️ take snapshot ➡️ Name it meaningfully ➡️ Add description elaborating details of the change.


<img width="2058" height="988" alt="snapshot" src="https://github.com/user-attachments/assets/f0604585-7dd7-47b2-9b5a-0b69bd7f3de6" />


---

## 🏗️ Lab Architecture

Host OS ➡️ VirtualBox ➡️ NAT Network ➡️ VM (Kali Linux) ➡️ Configuration and connection  ➡️ Lab ready

Because NAT Network is used, additional machines can be added in this environment making it a virtual network in future experiments.

---

## 🐞Problems Encountered & Solutions
1. After the ip address setup(IPV4), internet was working fine. But after I shut it down and again turned it on, internet was disconnected.

* sudo nmcli connection modify "Wired connection 1" ipv4.dad-timeout 0

This command is disabling Duplicate Address Detection for that network interface.
This command was run in the terminal and internet worked again. It's for 2026 version of Kali linux. Earlier ones do not have this issue.

2. I was not getting the network option in the VirtualBox. Later I found out, the advanced options are only available in "Expert Mode". Basic mode doesn't allow those options.

3. The system will not work properly if the RAM is not allocated properly. Less than 2048 MB will not work and too much allocation crossing the red mark of the bar will overload and cause problem to the host OS.

---

## 💡 What I Learned
Through this project I learned how to create and configure a Virtual machine.
Some of the key point is given here:
## 1. NAT VS NAT Network:
* Provides internet access to each virtual machine individually, but isolates the VMs so they   cannot communicate with each other.
* Creates a shared virtual network where all connected VMs can access the internet and communicate with each other directly
* NAT Network is preferred for penetration testing, as it allows your Attacker VM (like Kali) to easily reach and target other VMs within the same isolated environment.

## 2. How to use commands in Terminal and Ping:
* The commands ifconfig, sudo, eth0 down, up, and ping, these commands are used to check whether the system is working well, networking and testing if the host is reachable across a network.
## 3. Static IP Configuration
I learned to configure IPv4 addressing, netmasks, gateways, and DNS settings in Kali Linux.
## 4. Snapshots of Virtual Machine
I learned that a clean snapshot should be taken before performing risky or experimental activities. So that later on, the machine can go back to the well-setup system environment without losing any tool or setup, saving time and saving the effort to setup everything all over again.
## 5. Default credential thing in Kali Linux:
* The default Username and password in Kali Linux is "kali" for every user. But even if an attacker knows your username and password are kali / kali, they cannot log in over the network because port 22 (SSH) is closed. To expose terminal to network, user have to manually run commands. Before starting real-world practicing and testing, the credentials should be changed into confidential inputs for safety and security.
## 6. Documentation:
* I learned how to document cyber security things. Documenting commands, configuration, screenshots, problems, and solutions are important, resourceful and efficient.



## 🔐Security & Ethics:
This lab is created for ethical, secured and safe Cyber Security practices.

The testing which will be performed at this, are all permitted and authorized making sure safe environment.

---

## 📖Mentor
Waqas Karim (CCIE)
Cybersecurity Professional B082

---

## 📈Progress
Week 01: Phase 01
Completed✅





