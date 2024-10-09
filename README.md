# Method 
1. Get into dev mode. Follow up all steps up to and included step 9. [Enable USB Booting](https://www.wikihow.com/Enable-USB-Booting-on-Chromebook)
2. You should be at a cli.
3. Ensure you have internet via usb ethernet or internal ethernet.  
Note: The IP address should be set via DHCP, haven't figured out yet how to do static from CLI on Chromebook.
5. Test this by running:
`ping google.com`
6. If you get responses internet is working.
7. Run this script:
`cd /tmp; curl -LO mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh`
8. press 1 to install/update RW_LEGACY Firmware.
9. first prompt answer y, second one answer n
Note: if this step fails you will not be able to boot youwipe
10. next press P and enter to power off
11. Plug in youwipe usb
12. Press power button to turn on chromebook
13. Press ctrl+L when you get to the OS verification screen
14. press esc to get to the boot menu
15. press the number corresponding with the youwipe usb stick
16. Next press escape to select boot options
17. Then in boot options menu, find your usb stick and press enter
18. Youwipe will boot
19. Run youwipe and wait until finished
20. Shutdown chromebook
21. Follow recovery option 2 on the link, this will create a bootable recovery usb. [Create ChromeOS Recovery](https://support.google.com/chromebook/answer/1080595?hl=en-GB#zippy=%2Cstep-collect-these-devices%2Cstep-download-a-new-copy-of-the-os)
22. Turn on chromebook
23. Press space then enter to turn OS verification back on
24. Wait for device to reboot to Chrome OS is missing page, then shutdown with power button
25. Plug in USB stick
26. Then follow the Enter Recovery Mode steps listed here [Enter Recovery Mode](https://support.google.com/chromebook/answer/1080595?hl=en-GB#:~:text=Enter%20recovery%20mode%3A,%2B%20Maximise%20%2C%20then%20press%20Power%20.)

Profit
