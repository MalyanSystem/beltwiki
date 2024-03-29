
## Welcome To Join Malyan Family!

 Thank you for choosing Malyan 3D Printer and start a
pleasant journey with Malyan 3D Printer to turn your
imagination into reality!

 Please find software and user manual in the memory
card come with our product, or you can download them
from this wiki. It is imperative that you
read the operating instructions carefully before operating
Malyan 3D Printer.

 You can visit our wiki to find more support and FAQ. If
you have further questions or advice, please write email to
[support@malyansys.com](support@malyansys.com). 

 We wish you have a good experience of using Malyan
3D Printer and we are appreciated with your continuous
support! 
<br>

## Installation Instruction

[MA20 Installation Instruction](https://malyansystem.github.io/beltwiki/install-ma20.pdf): 
<embed src="https://malyansystem.github.io/beltwiki/install-ma20.pdf#toolbar=0&navpanes=0" width="800" height="560" type="application/pdf" />
<br>

[MA21 Installation Instruction](https://malyansystem.github.io/beltwiki/install-ma21.pdf): 
<embed src="https://malyansystem.github.io/beltwiki/install-ma21.pdf#toolbar=0&navpanes=0" width="800" height="560" type="application/pdf" />
<br>

## User Manual

[MA20 User Manual](https://malyansystem.github.io/beltwiki/manual-ma20.pdf): 
<embed src="https://malyansystem.github.io/beltwiki/manual-ma20.pdf#toolbar=1&navpanes=0" width="800" height="800" type="application/pdf" />
<br>

[MA21 User Manual](https://malyansystem.github.io/beltwiki/manual-ma21.pdf): 
<embed src="https://malyansystem.github.io/beltwiki/manual-ma21.pdf#toolbar=1&navpanes=0" width="800" height="800" type="application/pdf" />
<br>

## Installation Video
<embed src="https://youtu.be/MXVKs4bbYU8" width="800" />
[Youtube Link](https://youtu.be/MXVKs4bbYU8)
<br>

## SDCard file

You can download sdcard content from ~~google drive link for [MA21](https://drive.google.com/file/d/15IfQ0M8NjdaZk3vqWLoW4mX7K6FlmysM/view?usp=sharing) and [MA20](https://drive.google.com/file/d/1Qx9RW9jHeNj5DZ9rDJ7dUP1Kmx_iQ_P0/view?usp=sharing).~~ Google drive link is broken, please check onedrive link: [MA21](https://1drv.ms/u/s!AlGInf7rhmaOm51k8upJ8VwFSiTT2A) and [MA20](https://1drv.ms/u/s!AlGInf7rhmaOm51lXzZbj4oQ6abyrw)

## WiFi Configuration (MA20 & MA22)
Note: Prior to activating WiFi on your device, please be aware that the MA20 & MA22 solely support 2.4GHz WiFi rather than 5GHz. If your router combines these two frequency bands, kindly ensure to distinguish them properly to allow the device to detect your WiFi network. Additionally, avoid using the same SSID for both your 2.4GHz and 5GHz WiFi networks.

1. Create a new text file and input the following: 
![](./img23052201.png)

2. Insert the SD card into the printer and execute the "wifi.gcode" file. After that, restart the machine and wait for the IP address to appear on the screen.
![](./img23052202.png)

## Firmware update instructions

### MA20: [Firmware link](https://malyansystem.github.io/beltwiki/Firmware(V245-215).rar)

>0. Download the firmware from above link and open compressed file.
>1.	Copy UPDATE.BIN & LCD.BIN files to microSD card. 
>2.	In select print file menu, choose UPDATE.BIN will start to update firmware for motion controller. Machine will reboot after successfully updated. Don’t power off machine during updating. 
>3.	Update UI controller: 
>    1. Power off machine and move X and Y axis by hand to trigger end stopper. 
>    2.	Pressed the rotary button and power on printer, don’t release rotary button. 
>    3.	Until two fan start to spin, indicate firmware have started to update, release rotary button. 
>    4.	It will take approximate 4 minutes to finish. LCD panel will reboot and show new version string. 
>    5.	Please don’t forget to delete update file to avoid enter firmware update again. 
>4.	Choose M502.gcode in print file menu to clear EEPROM in printer. 

<!--
### MA21: [Firmware link](https://malyansystem.github.io/beltwiki/ma21update.bin)

> 1. Download the firmware from above link.
> 2. Rename file name to "update.bin" and copy to FAT32 formatted CLEAN micro SDCard.
> 3. Select "update.bin" file to print. And wait few minutes for update.
> 4. New version string will show up in LCD screen after successful update.
-->

