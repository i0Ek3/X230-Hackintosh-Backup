# X230 Hackintosh

**I no longer use hackintosh on my X230 laptop, if you want to know more, just check [5T33Z0](https://github.com/5T33Z0)'s awesome work on [T530](https://github.com/5T33Z0/Lenovo-T530-Hackintosh-OpenCore). **

> **macOS(Mojave & Catalina & Big Sur) on Lenovo ThinkPad X230 i5-3320 without any modified.**

This repo is a backup of X230 hackintosh EFI files, which support Mojave/Catalina/Big Sur. If you wanna use this EFI, please go to release page to download EFI which you need, you'd better add your own serial number and mlb information on that.

![x230](https://github.com/i0Ek3/X230-Hackintosh-Backup/blob/master/pic/X230.jpg)

## X230 Configuration

- CPU: Intel i5-3320M
- Graphic: Intel HD Graphics 4000
- Mem: Cuso 8GB x 2
- SSD1: Cuso 480GB for Windows 10
- SSD2: Samsung Evo 500GB for macOS
- Wifi Card: stock one, use itlwm to fix wifi issue
- Screen: stock one

## Getting Started

Actually I already do not customize my own EFI config files, I modified somthing on [@banhbaoxamlan](https://github.com/banhbaoxamlan/X230-Hackintosh)'s version to make it work well. So if you have the same type X230 of mine, you can replace the EFI for your X230 while you installed macOS. Also you can contribute your own commit on that.

## macOS Support Version

### Big Sur

In this version, nothing should be worried. Cause of this version I use @banh's EFI and I modified a little make it work well. 

What you got in this EFI? Just try it! Of course change your own CPU model's SSDT-PM.aml 

### Catalina

In this version, you need know:

- Original wifi card AR9285 can be worked in Catalina, but you need find a way to make that, I'm not do it!
- Touchpad just have basic function like move, multi finger gestures are all not work, no fix.

### Mojave

Nothing should be worried on this version or I forgot, try yourself.

![Mojave](https://github.com/i0Ek3/X230-Hackintosh-Backup/blob/master/pic/desktop.png)

## Issues

You can visit [here](https://github.com/i0Ek3/GotIssue/blob/master/macos.md) to find the solution.

## Credit 

Those guys who contribute on GitHub and Hackintosh platform, expecially [@banhbaoxamlan](https://github.com/banhbaoxamlan/X230-Hackintosh).
