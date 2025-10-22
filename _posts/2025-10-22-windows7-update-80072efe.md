---
layout: post
title: "Windows Update Error 0x80072EFE Solution"
categories: [windows]
tags: [update, error, 0x80072EFE]
---

This error usually occurs due to **DNS** or **network configuration** problems.  
Follow the steps below to solve it:

1. Reset network settings: *Settings > Network & Internet > Advanced network settings > Network reset*  
2. Change DNS: set IPv4 to `1.1.1.1` and `8.8.8.8`  
3. Run Command Prompt (Admin) and type:
ipconfig /flushdns
netsh winsock reset
netsh int ip reset
4. Restart your computer.

**Download:** [Wi-Fi Fix Tool (ZIP)](/files/fix_wifi.zip)
