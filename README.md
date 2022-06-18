# Coolray Easy App installations via ES File Manager


Add features to your Coolray headunit by installing Android apps.

- Install/Uninstall any APK compatible with Android 4.3.
- Enable Carplay with Autokit + Carlinkit Dongle
- Enable Android Auto via HeadUnitReloaded
- Connect to wifi
- Standalone Waze/Maps (via usb dongle)
- Install what you **only need**


## Requirement:
- 1 USB Flashdrive formatted to Fat32.
- Compatible firmware 84, 93, 96, 20, 22, and 32.

## Overall steps
1. Install ES File Manager via ES Installer script.
2. Install apps via ES File Manager from your flashdrive.

### ES installation step by step:
1. Download [`ES Installer.zip`](https://github.com/coolrayinfotainment/customs/raw/main/ES%20Installer.zip)
2. Format the flashdrive to fat32 (recommended to always format the flashdrive with fat32 before copying files)
3. Extract and copy all files from the `ES Installer.zip` to the root of the flashdrive.
<img width="670" alt="image" src="https://user-images.githubusercontent.com/6368863/174067102-5e050c00-e189-4687-824d-63800f332caa.png">

5. Unplug the flashdrive from the computer.
6. Start your car, wait for your headunit to fully start.
7. Plug the flashdrive to the car right usb port.
8. Don't press anything, just wait for the reboot and head unit to fully start.
9. Remove flashdrive.
10. Check the ES File Manager on the menu.

### App installation step by step:
1. Download any apk compatible with Android 4.3.
2. Copy the apks to the flashdrive. Then eject from computer.
3. Insert to car usb port.
4. Open ES File Manager, navigate to the flash drive.
5. Open and install the apks.
  - If it prompts installation block (usually the first time)
    - Tap settings then check `Unknown Sources`
6. Repeat step 1 if you want to install more apps.

## Frequently installed apps

- Autokit for Carplay [Download](https://tbox.carlinkit.cn/autokit_2022.apk)
- Waze/Maps (gps dongle setup needed)
- Spotify
- Netflix
- Launcher
- Wifi

Just search any compatible apks. (I heard you can find some from apkpure or apkmirror 🏴‍☠️)

Android 4.3 compatible apps are limited and note that not all are compatible with our unit. 

I would suggest to keep the app install to the bare minimum. Our unit is equivalent to a midrange phone around 2012.

**Do not install Google Playstore or any google services. **

You could join this telegram group chat to see and download community tested apks for coolray.

<img width="330" alt="image" src="https://user-images.githubusercontent.com/107626736/174421917-335e2a6b-9559-473b-838b-7154b574e018.png">

https://t.me/apkcoolray

### How to uninstall
1. Open ES File Manager
2. From the side menu go to Apps.
3. Select app to uninstall.

## How to remove ES and all 3rd party apps
1. Go to settings and reset factory settings.

## Notes
- The script will not reflash your headunit, it will just install the ES File Manager, so that you could install apps easier.
- This can be easily reverted by `resetting to factory settings` from the settings.
- This will not root your device, unless you install kingroot.

## Tested
- 2022 Coolray SE Sports | H50.00032

## Support
Nope, I won't give support personally as I hope this is already a noob friendly guide.

I'm hoping this will spark a free 'modding' community for our headunit.

Let's utilize the issues tabs so that we could improve this document and pseudo support.

Pull request are welcome!

## Wishlist/To do
- [ ] Step by Steo Screenshots
- [ ] Updated tested unit list
- [ ] Community support

## Will this void my headunit warranty?
Let's assume the worse, yes! But if you are paranoid, you could just reset to factory default before going to any dealership.

## Disclaimer
The script is from a [Russian forum](https://4pda.to/forum/index.php?showtopic=1001500&st=600#entry107246765) made for their Coolray but compatible to PH Coolrays. Kudos to them.
I will not be liable for any damages that will happen to your device when you install system breaking apps.
