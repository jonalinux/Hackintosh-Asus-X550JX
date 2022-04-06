# macOS-on-ASUS-X550JX-(Big Sur 11.6.3)

# Monterey 12.0.1
(5 Feb 2022) For macOS Monterey 12.0.1 Disable HS80211Family.kext and Ath3BT.kext in config.plist because Don't Work - KP (Kernel Panic on Boot)

# Big Sur 11.6.3
info:

1. OS:                             macOS Big Sur Version 11.6.3 (Build 20G415)
2. Model Identifier:               MacBookPro11,5 - Year 2015
3. CPU:                            Intel(R) Core(TM) i7-4720HQ CPU @ 2.60GHz
4. Intel Generation:               Haswell
5. RAM: 8 GB Total  (Hynix/Hyundai DDR3 1600 MHz 4.00 GB + Samsung DDR3 1600 MHz 4.00 GB)
6. GPU1: Intel HD Graphics 4600 VRAM 1536 MB
7. GPU2: Nvidia 950M 4GB (don't work)
8. QCA9565 / AR9565 Wireless Network Adapter: (pci168c,36)
9. Qualcomm Atheros Bluetooth (0x13d3 0x3408)
10. Realtek 8411B PCI Express Gigabit Ethernet
11. Audio Conexant CX20751/2 (layout-id 3)

![Screen Shot 2022-02-05 at 18 34 06](https://user-images.githubusercontent.com/87201918/152656713-8a77f7be-a319-4d64-a6d7-2963dcc2e71d.png)

# Post Install

# How to install Audio Connexant

![Screen Shot 2022-02-05 at 19 55 53](https://user-images.githubusercontent.com/87201918/152656882-70cb9cb6-0242-4c0a-b970-96e8a96f10f0.png)
![Screen Shot 2022-02-05 at 19 57 24](https://user-images.githubusercontent.com/87201918/152656920-e3f693e8-e450-40c1-8c02-be01ab9387ba.png)



Use https://github.com/headkaze/Hackintool to install in L / E (Library / Extensions), voodooHDA.kext that you find in the Kext folder of the EFI-Post-install archive.
![Screenshot 2021-07-02 at 11 57 55 AM](https://user-images.githubusercontent.com/87201918/152656564-e88e1343-e650-4283-83d3-6731ac527d0a.png)

After you have installed go to System Preference and open Security and Privacy: press allow and restart the system.

![Screenshot 2021-07-02 at 11 54 00 AM](https://user-images.githubusercontent.com/87201918/152656571-ecb9adc4-08a8-425a-940e-ec28d832c1ba.png)

For more information see here https://github.com/yahgoo/installVoodooHDA4BSnMont



 

