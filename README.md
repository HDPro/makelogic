LOGIC ANALYTICS WITH CY7C68013A BOARD
====
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_1.png">

### INSTALL SOFTWARE

##### DOWNLOAD AND INSTALL: [EZ-USB™ FX3 SDK (*)](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.ezusbfx3sdk)
(*): "EZ-USB™ FX3 SDK" need Free Infineon Account to download. It provide driver for CY7C68013A and software to programing eeprom.

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_2.png" width=800>
</p>

##### DOWNLOAD AND INSTALL: [PulseView (*)](https://sigrok.org/wiki/Downloads)
(*): I try install PulseView Nightly Build but start button not working. Then I try PulseView Release Build. It works well kkk.

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_3.png" width=800>
</p>

##### DOWNLOAD: [EEPROM Configuration.iic](https://raw.githubusercontent.com/HDPro/makelogic/main/EEPROM%20Configuration.iic)

### SETUP CY7C68013A BOARD

##### (STEP 1) REMOVE LEFT JUMP IN BOARD

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_4.jpg">
</p>

##### (STEP 2) INSTALL DRIVER FOR CONTROL CENTER

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_5.gif">
</p>

##### (STEP 3) DOWNLOAD PROGRAM FOR BOARD
Run: Control Center (C:\Program Files (x86)\Cypress\EZ-USB FX3 SDK\1.3\bin\CyControl.exe)<br>
The operation is similar to the gif below then unplug USB cable and plug it back in.

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_6.gif">
</p>

##### (STEP 4) INSTALL DRIVER FOR PULSEVIEW
Run: Zadig (C:\Program Files (x86)\sigrok\PulseView\zadig.exe)

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_7.gif">
</p>

##### (STEP 5) RUN PULSEVIEW
Run: PulseView (C:\Program Files (x86)\sigrok\PulseView\pulseview.exe)<br>
Then Unknown Device become fx2lafw

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_8.png" width=800>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/HDPro/makelogic/master/images/image_9.gif">
</p>