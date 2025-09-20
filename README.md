# Lenovo-bootloader-Unlock-Code-SN-Generator
A secure, local SN.img generator for Lenovo new-generation devices. This tool helps generate the bootloader unlock file directly in your browser without sending any data to external servers.

How to Use

Get your device bootloader SN via:

fastboot getvar all


Or:

adb shell getprop ro.boot.bootload_sn


Make sure the SN is 64 characters long.

Paste it into the input field in the browser.

Click Generate to download sn.img.

Use the file to unlock bootloader:

fastboot flash unlock sn.img
fastboot oem unlock
