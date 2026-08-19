---
layout: single
title: "Install NewPipe via ADB"
categories: 일상
tag: [google, recruiting]
author_profile: false
---
<p>2026-05-20 작성</p>

<p>구글정책변경으로 <a href="https://newpipe.net/">NewPipe</a>를 계속 사용하려면 다른 방법을 써야한다.</p>

<p><a href="https://github.com/woheller69/FreeDroidWarn?tab=readme-ov-file#solutions">woheller69/FreeDroidWarn</a>에서 알려주는 방식대로 ADB를 통해 설치할수 있다.</p>

## Solutions
- Install apps via ADB. Google has already confirmed that ADB will continue to work in the future. You can either use ADB from a PC as described below or use a wireless ADB based installer like [anyapk](https://github.com/sam1am/anyapk).

### Set up ADB on your device
- Enable Developer options on your phone: In Android settings, find and tap the Build Number option (usually at the bottom in "About phone") seven times until you see the message "You are now a developer!"
- Return to the main Settings screen to find Developer options at the bottom (or it may be in System)
- Scroll through the options to find and enable USB debugging. On some devices, you can use the hourglass at the top of the Settings app to search for "USB debugging".

#### Download ADB for PC (Windows) 

Download these files into a folder:

- [AdbWinApi.dll](https://github.com/K3V1991/ADB-and-FastbootPlusPlus/blob/main/AdbWinApi.dll?raw=true)
- [AdbWinUsbApi.dll](https://github.com/K3V1991/ADB-and-FastbootPlusPlus/blob/main/AdbWinUsbApi.dll?raw=true)
- [adb.exe](https://github.com/K3V1991/ADB-and-FastbootPlusPlus/blob/main/adb.exe?raw=true)
- [APK_Installer.bat](https://github.com/woheller69/FreeDroidWarn/blob/master/APK_Installer.bat?raw=true)

#### Download app APK

You will also need the APK file to install to your phone, e.g. from [F-Droid](https://f-droid.org/). Save the APK to the same folder where you downloaded the above files.

#### Connect phone to USB and install app

- Connect your phone to the PC via a USB cable.
- You should see a notification on your phone to change USB mode. Set it to file transfer mode.
- Open the folder where you saved the above files and double click `APK_Installer.bat`.
- Select desired APK from list and install.
- If prompted, check confirmation box on phone and agree to USB debugging from this PC.

Your app will be installed 🚀

Optional (**recommended**): Switch off USB debugging in Developer options until you need it again.




<p>샤오미 스마트폰 사용자라면 <br/>
- 샤오미 <a href="https://account.xiaomi.com/">회원가입</a>이 되어있어야 한다. (공기기라면 SIM칩을 넣어두어야 USB설치모드를 켤수 있음) <br/>
- 개발자옵션 (설정> 일반> 개발자옵션> USB디버깅)<br/>
- "USB로 설치" 켬
</p>

<p>삼성 갤럭시폰 사용자라면 <br/>
- 설정 > 보안 및 개인정보 보호 > 보안 위험 자동 차단 "off"
- 개발자옵션 > USB 디버깅 "on"
<br/>
- 설치후, 설정 > 보안 및 개인정보 보호 > 보안 위험 자동 차단 "on"
</p>