- 👋 Hi, I’m @whitehax0r a.k.a (razr2312) on Twitter
- 💞️ I’m looking to collaborate on PS4 Linux community and other interested stuff.
- 📫 How to reach me at the end of this file.
<!---
whitehax0r/whitehax0r is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# ArchLinux-PS4v2

This is a compiled and updated Arch Linux with some personal changes more related to GUI to look better and some emulators.

![desktop2](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/2ba4c9d407440a07d327011caef73b2786445ff3/Desktop.png)

# Features

## Everything has been updated until August 23/2022

- Parallel Downloads enabled.
- Updated PS4 drivers with latest stable Mesa, libdrm and xf86-video-amdgpu.
- LightDM with autologin enabled window manager.
- Neofetch - Show general information about this system.
- XFCE - Desktop Environment.
- Steam - The ultimate destination for playing, discussing, and creating games.
- Lutris - Play all your games on Linux. Lutris is an Open Source gaming platform for Linux.
- ExFat file system support.
- Bluez - For bluetooth pairing PS4 controller.
- Blueberry - GUI compatible with XFCE/GTK.
- Duckstation - Best PSX emulator.
- Flatpak - Next generation technology for building and distributing desktop application on Linux.
- Dolphin emulator - Nintengo Wii and Gamecube emulator.
- Nano - Text editor.
- Chromium - Web browser.
- Powerlevel10k - ZSH terminal.
- PCSX2 - Playstation 2 emulator with vulkan support.
- Yabaouze - Sega Dreamcast emulator.
- Hacknerdfonts - For icons inside ZSH and customized fonts for terminal.
- RetroArch - Multiplatform emulator.
- Minecraft Java - Because is fun. :pick:
- LSD - Powered LS bassically.
- BAT - Powered CAT bassically.
- VLC - Video player.
- Spotify - Music player.
- Yay - Yet another yogurt. Pacman wrapper and AUR helper written in go.
- Zip - Compress files to zip files.
- Unzip - Uncompress zip files.
- P7zip - Commandline 7zip support for Linux.
- Htop - See process and other stuff.
- FeralGameMode - Is a daemon/lib combo for Linux that allows games to request a set of optimisations be temporarily applied to the host OS and/or a game process.
- WineStaging - Wine is a compatibility layer capable of running Windows applications on several POSIX-compliant operating systems, such as Linux, macOS, & BSD.
- Wine GE on Lutris - WINE based on/forked from the most recent bleeding-edge proton experimental wine repo. This is meant to be used with non-steam games outside of Steam.
- ProtonVPN - High-speed Swiss VPN that safeguards your privacy.

# Mandatory requirements
- A brain xD and a lot of patience.
- USB|HDD|SDD 3.0
- USB hub for connect more usb devices. (optional)
- USB or Bluetooth Mouse and keyboard.

# My PS4 Hardware

- PS4 Slim
- Firmware 9.00
- Model CUH-2115B.
- SouthBridge Baikal with Liverpool.

⚠️ If you have a PS4 Fat or PS4 Pro version check in the little FAQ for more details. Read the complete guide first please. ⚠️

## If you have same PS4 hardware as me you can use these files from below:

- [bootargs.txt](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bootargs.txt) or [Download here](https://mega.nz/file/2qBCTJpR#CTD_nQOLFsrBMcau-KS6QitasbuVAXx_PPN22Wk2qoo) MD5 >__C84AD779CE76762C04CBF80E420E324D__
- [initramfs.cpio.gz](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/c01e7d6162ad8029748b408f930f5b9952734418/initramfs.cpio.gz) MD5 >__826d6e22c76ded87e18df7ceba8a9630__
- [XanMod bzImage-baikal](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/3766ae7a6b7f3f47b705f90e6ad4df168cf4d47e/bzImage) MD5 >__7d460b453c9fec3f2f99be0667d18cc1__
- [XanMod bzImage-baikal-1.9Ghz](https://github.com/whitehax0r/ArchLinux-PS4v2/blob/8363f7fdfc1a0a37d59430b5aedd008b0ee57cad/bzImage1.9) MD5 >__cb5b65295ea9b34d6d1a4e8cb9c3cc8b__
- [archv2.tar.xz](https://mega.nz/file/vn5glJbB#ZWSZA7scPuyx1UkOiM_UW7NoUxxMc_L3pJGiUWKbmRI) MD5 >__8bbd77efb78250a8d5eba6cd0201bb54__
- ⚠️ Don't forget to rename this file archv2.tar.xz to psxitarch.tar.xz ⚠️ 

# Preparing your PS4 system.

- Make sure you are on firmware 9.00.
- Go to Settings>Sound and Screen>Video output Settings>
- Resolution set to >__1080p__
- RGB range se to >__Full__
- HDR set to >__Off__
- Deep color output set to >__Off__
- Then go to Setting>System>
- Uncheck the box "Enable HDMI Device Link"
- Uncheck the box "Enable HDCP"

# Traditional Method 

## Preparing your USB|HDD|SDD 3.0 Device for ArchLinux-PS4v2

:warning: Highly recommeded to use a USE A >=16GB USB 3.0 Device :warning:

- Format the USB|HDD|SDD 3.0 Device to Fat32 filesystem. You can use this [software.](http://ridgecrop.co.uk/index.htm?guiformat.html)
- Copy and paste the bzImage, the initramfs.cpio.gz, bootargs.txt and psxitarch.tar.xz files to the root of the USB|HDD|SDD 3.0 Device.
- :warning: If you use the same initramfs.cpio.gz from this Github project, the name of this OS should be psxitarch.tar.xz :warning:
- The total of 4 files should be on the root of your USB 3.0 Device bzImage, the initramfs.cpio.gz, bootargs.txt and arch.tar.xz or psxitarch.tar.xz.
- Then connect your USB 3.0 Device with all the needed files to your PS4, make sure to connect the USB|HDD|SDD 3.0 Device and the USB slot that is near from the PS4 Blue-ray Disc Drive.
- Open the PS4 web browser and launch the JB+LINUX (VRAM 1GB) payload, use this [one](https://sleirsgoevy.github.io/900-host/).
- Follow the instructions in order to jailbreak your PS4.

## First Run Linux installation

- When you are on the rescueshell type the following commands:
>__exec install-psxitarch.sh__
- When the installation is done ArchLinux-PS4v2 is going to boot automatically, if not type the following command:
>__exec start-psxitarch.sh__

If you got an error like this one: "mount -o ro /newroot failed" just type the following commands:
>__mount -o ro /newroot__
- then again
>__mount -o ro /newroot__
- Now type this:
>__exec start-psxitarch.sh__
- and should boot now to ArchLinux-PS4v2 :)

## Post installation steps (for the ones who follows the Traditional Method)

- Connect your USB|HDD|SDD 3.0 to a computer and copy again the [bootargs.txt](https://mega.nz/file/2qBCTJpR#CTD_nQOLFsrBMcau-KS6QitasbuVAXx_PPN22Wk2qoo) file in the root of the FAT32 partition.
- Jailbreak again your PS4 with Sleirsgoevy [host](https://sleirsgoevy.github.io/900-host/) and then click on >> select JB+LINUX (VRAM 1GB) payload.
- You will be again in the rescueshell, just type:
>__exec start-psxitarch.sh__

If you got an error like this one: "mount -o ro /newroot failed" just type the following commands:
>__mount -o ro /newroot__
- then again
>__mount -o ro /newroot__
- Now type this:
>__exec start-psxitarch.sh__
- and should boot now to ArchLinux-PS4v2 :)

# Recommended method

You need a computer with Linux in order to follow this steps. This method is faster and better than the traditional one.

- Connect your USB|HDD|SDD 3.0 to your computer with the linux of your preference.
- If you are using Ubuntu type the following command sudo apt-get install gparted.
- If you are using Arch type the following command sudo pacman -Sy gparted.
- If you are using Fedora type the following command sudo dnf install gparted.
- Run Gparted.
- Make sure you are selecting your USB|HDD|SDD 3.0 on gparted.
- Create the first partition with 300 MB with FAT32 format. (No label name needed)
- Create a second partition with the label name psxitarch and then format the partiton to EXT4 format.
- Close gparted and mount the new partitions you have created in your USB|HDD|SDD 3.0, now you are ready to install ArchLinux-PS4v2.
- Copy and paste the bzImage, the initramfs.cpio.gz, bootargs.txt files to the root of the FAT32 partition.
(Asuming the psxitarch.tar.xz is in the Downloads folder) 
- Open the Terminal and type the following commands:
>__sudo tar -xvJpf /home/$USER/Downloads/psxitarch.tar.xz -C /media/$USER/psxitarch__
- Once this finish, eject safely your USB|HDD|SDD 3.0 from your comptuter.
- Then connect your USB 3.0 Device with all the needed files to your PS4, make sure to connect the USB|HDD|SDD 3.0 Device and the USB slot that is near from the PS4 Blue-ray Disc Drive.
- Open the PS4 web browser and launch the JB+LINUX (VRAM 1GB) or (VRAM 3GB)payload, use this [host](https://sleirsgoevy.github.io/900-host/). 

## Post installation steps (for the ones who follows the Recommended Method)

- Connect your USB 3.0 Device with all the needed files to your PS4, make sure to connect the USB|HDD|SDD 3.0 Device and the USB slot that is near from the PS4 Blue-ray Disc Drive.
- Open the PS4 web browser and launch the JB+LINUX (VRAM 1GB) or (VRAM 3GB)payload, use this [host](https://sleirsgoevy.github.io/900-host/).

## Changing the System Time and Date

The first time you boot to ArchLinux-PS4v2 you need to fix the time and date. ⚠️Connect your PS4 to the internet by WiFi or Ethernet port first. ⚠️

Check first the list of time zones available typing the following command on the terminal:
>__timedatectl list-timezones__

For example mine is: America/Tegucigalpa

To set your time zone:
>__sudo timedatectl set-timezone Zone/SubZone__

For example in my case is: __sudo timedatectl set-timezone America/Tegucigalpa__

Then we will create a symbolic link to do this permanently:
>__sudo ln -sf /usr/share/zoneinfo/Zone/SubZone /etc/localtime__

For example in my case is: __sudo ln -sf /usr/share/zoneinfo/America/Tegucigalpa /etc/localtime__

Now we will enable NTP just type this on the Terminal:

>__sudo timedatectl set-ntp true__

Now just wait about 5~10 seconds and you will see your date and time will change automatically to your zone.

# Recommended emulators and tips:

- RPCS3 - PS3 emulator. (You can try with the AppImage in their [website.](https://rpcs3.net/download))
- PCSX2 - PS2 emulator. (You can try with the AppImage in their [website.](https://pcsx2.net/downloads/#nightly-anchor))
- Nintendo Switch emulator. (You can try with the AppImage in their [website.](https://yuzu-emu.org/downloads/))

If you will run games on Wine, Swap should be enable, run the following commands:

>__sudo dd if=/dev/zero of=/swapfile bs=1M count=8192 status=progress__

>__sudo chmod 0600 /swapfile__

>__sudo mkswap -U clear /swapfile__

>__sudo swapon /swapfile__

Finally, edit the fstab configuration to add an entry for the swap file: 

>__sudo nano /etc/fstab__

Copy and paste this at the end of the file:
/swapfile none swap defaults 0 0

On your keyboard press CTRL + O and then "yes" to save the changes.
Then CTRL + X to exit from Nano.

Now you can close the terminal. 

# Know Issues

Not sure why but every time you boot in to linux, you have to unpair and pair again your PS4 controller.

# Some FAQs

## What is the password for the users "sony" and "root"?
You can find that on the Desktop, you will see a text fille called Important.txt

## Got black screen
Make sure your display is compatible with the 1080p resolution, if you still have a black screen try a others monitor or TV. Also make sure you follow the section of "Preparing your PS4 system."

## I want to uninstall this OS from my USB 3.0 Device
Just format your device.

## How to update ArchLinux-PS4v2?
Just type the following command:
>__sudo pacman -Syu__
- and type "Yes" if there are packages with updates.

If more than 5 months has been passed when I released this Distro, type the following commands:
>__sudo pacman -Sy__
- then:
>__sudo pacman -S archlinux-keyring__
- then
>__sudo pacman -Syu__

## Can I use my DS4 controller as mouse?
Yes!, you can.

## I have difficulties to connect my DS4 controller, what can I do?
I will upload a video later.

## I'm not sure about my PS4 Hardware?
You can search [here](https://www.psdevwiki.com/ps4/Southbridge#Southbridge_revisions) or [here.](https://www.psdevwiki.com/ps4/)

## Where I can find those PS4 kernels and initramfs.cpio.gz for other PS4's hardware Fat and Pro version?
Well you can download those files from Hakkuraifu [Github.](https://github.com/Hakkuraifu/PS4Linux-Documentation)
There is a posibility my this distro will not work properly with the PS4 Pro due the MESA drivers.
PS4 pro requires a new complete distro with MESA that support GLADIUS. I will create a new ArchLinux-PS4v2 for PS4 Pro later.

# Social Medias

- You can follow me on [Twitter](https://twitter.com/razr2312)
- You can follow me on [YouTube](https://www.youtube.com/user/allank2312/videos)
- You can follow me on [Reddit](https://www.reddit.com/user/razr2312/)

![esta es una imagen](https://github.com/whitehax0r/ArchLinux-PS4/blob/353059a5bbb0a7f161ade53a56e374a6398d7c6a/Flag.png)
