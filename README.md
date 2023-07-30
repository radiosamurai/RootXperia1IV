# RootXperia1IV
Rooting guide for Xperia 1 IV

Step by step Rooting guide for Sony Xperia 1 IV
FOR UNLOCKING
1. You need unlock your Xperia 1 IV first for unlocking go to settings click more and click build number so many times it will prompt your pincode for developer options after you enabling developers options go to developer options and open "OEM Unlocking" and ADB debugging.
2. You also need installed drivers + adb for Xperia 1 IV you can find in my repo too.
3. After all of that open CMD inside ADB tools and type "adb reboot bootloader".
4. You will go bootloader of your "secured phone" now you need unlocking code for Xperia device.
"https://developer.sony.com/open-source/aosp-on-xperia-open-devices/get-started/unlock-bootloader"
5. Go this link and go bottom of page you will see "select your device" select your Xperia 1 IV and it will ask you IMEI code for unlock code type your IMEI code and it will give you unlock code save this.

!!!WARNING!!! THIS WILL WIPE ALL YOUR DATA INSIDE OF YOUR PHONE BE CAREFULL AND GET SOME BACKUP. !!!WARNING!!!


!!!WARNING!!! THIS WILL WIPE ALL YOUR DATA INSIDE OF YOUR PHONE BE CAREFULL AND GET SOME BACKUP. !!!WARNING!!!

7. After that come back to CMD and type "fastboot oem unlock ***" *** replaced with your unlock code.
8. And CMD will give you "OKAY" prompt so your device is now unlocked and wiped as well you need setup again.
9. Type "fastboot reboot" for rebooting to system it will take longer then normal reboot because it wiped.

FOR ROOTING

1. Download XperiFirm from XDA or my repo.
2. Open XperiFirm and select your device code mine is XQ-CT72 Taiwan firmware edition.
   
!!!WARNING!!! YOUR PHONE FIRMWARE SHOULD MATCH WITH DOWNLOADED FIRMWARE BE CAREFULL WHEN YOU DOING THAT. !!!WARNING!!!


!!!WARNING!!! YOUR PHONE FIRMWARE SHOULD MATCH WITH DOWNLOADED FIRMWARE BE CAREFULL WHEN YOU DOING THAT. !!!WARNING!!!

![resim](https://github.com/radiosamurai/RootXperia1IV/assets/104136919/4076a3ad-3880-4c49-bb54-ffb7f40cf37b)

4. Select and click your firmware build number for downloading it will ask you a output path.
5. When it finished you will see a folder that contains firmware files like *.sin

 ![resim](https://github.com/radiosamurai/RootXperia1IV/assets/104136919/75291b37-ed15-45dd-8456-ec736a342691)
 
7. Download UnSin app from my repo or find from internet.
8. When you download UnSin app extract to firmware folder.
9. Open CMD on firmware folder and type "unsin.exe -dr" it will extract .sin files to .img ones.
10. When done, locate "bootboot_X-FLASH-ALL-*.img" and transfer this file to your Xperia 1 IV's download folder.
11. Install Magisk APP from Magisk repo in github (dont install from other websites this may be malware).
12. Open Magisk APP and click "Install" after that click "select and patch a file" you need to select your boot.img from download folder we putted in step 8.
13. When patch is done patched file saved in Download folder "magisk_patched-*.img" find this file in PC drag to your desktop (if you cant see in download folder on pc just unplug usb and put back in).
14. Now open CMD in ADB tools that you download from my repo type "adb reboot bootloader" when its in bootloader phone notification light will be "blue"
15. After all that we are going to flash or boot file with patched boot file so we need type "fastboot flash boot magisk_blabalba.img" so if it success CMD will return with "OKAY" after that just type "fastboot reboot" it will boot to system.
16. When boot to system open Magisk app and you will see its installed. Congratulations you rooted your Xperia 1 IV dont forget opening Zydisk for some bank apps.
