---
title: Treiber & Firmware
---

We already programmed the firmware. You only have to installed drivers and flash it on the NodeMCU (ESP8288). 
To communicate with the ESP8266 you need usb2serial drivers. The chipset for NocdeMCUs is usually CH341. Choose the link that corresponds to the operating system of your computer.

### Windows

##### Drivers for the old V2 model (CP2102) for Windows
* Windows 10: https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip
* Windows 7/8/8/8/8.1: https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip (32-bit version not supported for 64-bit version of system)

##### Driver for model V3 (CH341) for Windows
* Windows: http://www.wch.cn/downloads/file/5.html

##### Extract the downloaded file for Windows:
* for V2: Open the folder CP210x and double click on the application CP210xVCPInstaller_x64 (or x86)
* for V3: open the folder CH341SER and double click on the application SETUP.

---

### MacOS

#####  MacOS Drivers for the old V2 model
* MacOS: https://www.silabs.com/documents/public/software/Mac_OSX_VCP_Driver.zip (restart computer after installation)

#####  MacOS Driver for model V3
* MacOS: http://www.wch.cn/downloads/file/178.html (restart your computer after installation)

#####  Extract the downloaded file for MacOS.
* for V2: Open the folder CP210x and double click on the application CP210xVCPInstaller_x64 (or x86)
* for V3: open the folder CH341SER and double click on the application SETUP.

---

### Linux
#####  Drivers for the old V2 model
No drivers need to be installed. Chip should be supported directly (verifiable with dmesg)

#####  Driver for model V3
* MacOS: http://www.wch.cn/downloads/file/178.html (restart your computer after installation)

---
### Download Firmware Flasher 

* Windows (64-bit): https://luftdaten.info/flashtool/luftdaten-tool.zip
* Source Code: https://github.com/opendata-stuttgart/airrohr-firmware-flasher
* MacOS: https://luftdaten.info/flashtool/luftdaten-tool.dmg
* Source Code: https://github.com/opendata-stuttgart/airrohr-firmware-flasher
* Linux (64-bit): https://luftdaten.info/flashtool/luftdaten-tool.linux-x64
* Source Code: https://github.com/opendata-stuttgart/airrohr-firmware-flasher

### Install Firmware
Now connect the NodeMCU to the computer with a short micro-USB cable (the cable should not be longer than 1m, otherwise the installation may fail). Select the latest version `latest_en.bin` (or another language version) and click “Upload”.
Wait until the process is done and done. Now we assemble the sensor.
<br>
A big thank you goes to [Piotr, from Poland](https://dropbox.inf.re/), for his help! 🙋‍♂️ 

