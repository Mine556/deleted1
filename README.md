# how-to-root
Here I am describing the process how to root or mod ur Android especially Samsung device<br>
! * I'm not responsible for any bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed .<br>
! * Please * do some research... <br>
! * YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.<br>
! * Your warranty will be void if you tamper with any part of your device / software.<br>
------------------------------------------------------------------------------------------
OEM UNLOCKING & TWRP FLASHING
------------------------------------------------------------------------------------------

1. grab ur samsung +cable +pc(windows/linux) ODIN can be installed only on Windows on Linux u need to use HEIMDALL
2. download odin tool
3. download "twrp.img.tar"
4.  open settings > About Phone > Software Information >tap 7 times on BUILD NUMBER> go back to settings > Developer Options >Enable OEM Unlock/ing tap YES ......then plug ur device int pc reboot into DOWNLOAD MODE by pressing VOL-DOWN+PWR+BIXBY or HOME BTN
5. now u r in DOWNLOAD MODE 
6. open ODIN app select "AP" and insert in "AP" "twrp.img.tar" file
7. click "START" and wait ...
8. after Finish reboot ur device int RECOVERY by pressing VOL-UP+PWR+BIXBY or HOME BTN
9. "Allow Modifications" YES
10. now u are in  TWRP RECOVERY
------------------------------------------------------------------------------------------
INSTALLING MAGISK ROOT ZIP
------------------------------------------------------------------------------------------
1. download magisk .apk on ur PC, and platform-tools , exhtract platform tools open terminal (CMD) or POWERSHELL as an administrator ,...
2. in power shell type "cmd" now u are in CMD in POWERSHELL enter into dir "platform-tools"
3. rename it to magisk-ver.zip (from magisk-ver.apk)
4. select on ur device "ADB Sideload" type in CMD  "adb sideload magisk-ver.zip" wait....
5. now u have downloaded magisk into ur device
