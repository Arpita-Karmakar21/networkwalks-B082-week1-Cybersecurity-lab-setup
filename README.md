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

## Lab Configuration

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


## 🔗 Tools & Resources

---

* **7-Zip:** https://7-zip.org/download.html
* **VirtualBox:** https://virtualbox.org/wiki/Downloads
* **Kali Linux:** https://kali.org/get-kali

---

## Procedures:
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

## Step 6. Take a Clean Snapshot of the Virtual Machine
After the procedures, a VirtualBox snapshot was created.

<img width="2058" height="988" alt="snapshot" src="https://github.com/user-attachments/assets/f0604585-7dd7-47b2-9b5a-0b69bd7f3de6" />


---










