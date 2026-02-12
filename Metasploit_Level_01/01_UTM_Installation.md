# Metasploit Level 01
## UTM Installation Guide (macOS Intel)

### Introduction
In this project, I used UTM on macOS (Intel) to create virtual machines for Kali Linux and Metasploitable 2. UTM is a virtualization software that allows running different operating systems inside macOS.

---

## Step 1: Install UTM
- Downloaded UTM from: https://mac.getutm.app/
- Installed the application normally.
- Opened UTM and created a new Virtual Machine.

---

## Step 2: Create Kali Linux VM
- Selected "Virtualize"
- Chose Linux
- Selected downloaded Kali Linux ISO file
- Set RAM: 4GB
- Set CPU Cores: 2
- Created 40GB storage
- Network Mode: Shared Network

---

## Step 3: Import Metasploitable 2
- Used existing Metasploitable VMDK file
- Disabled UEFI Boot
- Attached Linux ISO temporarily to boot
- After boot, removed ISO
- Network Mode: Shared Network

---

## Result
Both Kali Linux and Metasploitable 2 are running successfully in UTM.

(Screenshots Here)
