# X230-Hackintosh-Backup

macOS(10.14.x support) on Lenovo ThinkPad X230. 

This is a backup for [f23258's](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1800217&highlight=X230) article, check it to know how to install macOS on X230. Big thanks to him.

Also you can visit [here](https://github.com/i0Ek3/BLANK/blob/master/2019/2019-06-12-X230.pdf) to know how to buy a X230 and made it happen.

Some issues you should know:

- WiFi network not work!
    - Change BCM94325HMB as your wireless card and programming that.
    - Set AirPortAtheros40.kext into System/Library/Extensions/IO80211Family.kext/Contents/Plugins then rebuild cache is not work for me.
    - I solved this issue through by a EDUP USB Wireless driver which named EP-N8508GS.
- Audio sometimes not work well.
    - Commonly I made X230 go to sleep then wake it up, the audio work well. 
    - Now, you can only set audio pannel in preferences the audio work well. 
    - Actually I need some time to fix this issue, maybe later.
- Touchpad just have basic function like move, multi finger gestures are all not work, I dont know why yet, fix later.
- No other problems or you tell me.

**Note: I use EFI file directly, it's work on macOS 10.14/10.14.5 which I test it by myself.**

Enjoy~

```
├── README.md
├── pic
│   ├── desktop.png
│   └── neofetch.png
└── tool
    ├── AirPortAtheros40.kext
    ├── Clover\ Configurator\ Global\ 5.4.4.0.dmg
    ├── HIDPI-EDID.command
    ├── Kext\ Utility.app
    ├── Wireless\ USB\ Adapter\ Clover-V7.pkg
    ├── X230-EFI-10.14.1-BCM94352HMB.zip
    └── ssdt-3320.aml

```

Some screenshots:

![](https://github.com/i0Ek3/X230-Hackintosh-Backup/blob/master/pic/neofetch.png)

![](https://github.com/i0Ek3/X230-Hackintosh-Backup/blob/master/pic/desktop.png)


