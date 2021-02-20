# Intel-Compute-Stick-OpenCore-Hackintosh
(m3/m5 model, no atom)

![Compute Stick](https://cdn.cnetcontent.com/d7/85/d785f29a-dc78-4e58-a9e0-31fcd360f826.jpg)
Tested with macOS 11.2

What doesn't work (yet):
1. eMMC internal storage (will likely never work)
2. SD card reader
3. CPU seems to report wrong

What does work that I've tested:
1. Acceleration
2. Audio over HDMI
3. Intel WiFi
4. Intel Bluetooth
5. Sleep/wake

Things to note:
The Intel BIOS is less than ideal and will remove the OpenCore boot entry, a temp work around is to enter the uefi shell, and type "fs3:" "cd EFI" "cd BOOT" "BOOTx64.efi" to start OpenCore

I'm not going to bother with a bad install guide yet since it's a bit janky
