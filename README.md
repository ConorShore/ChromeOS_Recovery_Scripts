# Method 
1. Get into dev mode. Follow up all steps up to and included step 9. [Enable USB Booting](https://www.wikihow.com/Enable-USB-Booting-on-Chromebook)
2. You should be at a cli.
3. Ensure you have internet via usb ethernet or internal ethernet.  
Note: The IP address should be set via DHCP, haven't figured out yet how to do static from CLI on Chromebook.
5. Test this by running:
`ping google.com`
6. If you get responses internet is working.
7. Run this script:
`cd; curl -LO mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh`
8. press 1 to install/update RW_LEGACY Firmware.  
Note: if this step fails you will not be able to boot youwipe
9. next press P and enter to power off
10. Plug in youwipe usb
11. Press power button to turn on chromebook
12. Press ctrl+L when you get to the OS verification screen
13. type 1 then press enter
14. Next press escape to select boot options
15. Then in boot options menu, find your usb stick and press enter
16. Youwipe will boot
17. Run youwipe and wait until finished
18. Shutdown chromebook
19. Follow recovery option 2 on the link, this will create a bootable recovery usb. [Create ChromeOS Recovery](https://support.google.com/chromebook/answer/1080595?hl=en-GB#zippy=%2Cstep-collect-these-devices%2Cstep-download-a-new-copy-of-the-os)
20. Turn on chromebook
21. Press space then enter to turn OS verification back on
22. Wait for device to reboot to Chrome OS is missing page, then shutdown with power button
23. Plug in USB stick
24. Then follow the Enter Recovery Mode steps listed here [Enter Recovery Mode](https://support.google.com/chromebook/answer/1080595?hl=en-GB#:~:text=Enter%20recovery%20mode%3A,%2B%20Maximise%20%2C%20then%20press%20Power%20.)
Profit
