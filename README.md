# Ventoyed Ultimate Saver
Live-os for All Needs | Repair Tools to Fix Any Problem | Linux, Windows & Android  
**in a Pen Drive**

## Ventoy (A new bootable USB solution)
[Ventoy](https://github.com/ventoy/Ventoy "GitHub Repo") is an open source tool to create bootable USB drive for ISO files.  
With ventoy, you don't need to format the disk over and over, you just need to copy the iso file to the USB drive and boot it.  
You can copy many iso files at a time and ventoy will give you a boot menu to select them.  
Both Legacy BIOS and UEFI are supported in the same way. 200+ ISO files are tested.  
A "Ventoy Compatible" concept is introduced by ventoy, which can help to support any ISO file.  

See https://www.ventoy.net for detail.

> You can rename pendrive by `sudo exfatlabel /dev/sdX1 VENUS`
>                              or
>                             add `-L VENUS` while installing ventoy to /dev/sdX

## Live OS
bootable computer operating system which runs directly from a pen drive
or similar storage device into a computer's memory, rather than loading from a hard disk drive.

### Manjaro Linux :green_heart:
[Manjaro](https://manjaro.org/ "official website") is a professionally made operating system that is a suitable replacement for Windows or MacOS.
Multiple Desktop Environments are available through our Official and Community editions.

An [Arch](https://www.archlinux.org/ "official website") based Linux distros.

*You can choose any linux distro which you comfortable with*

> for live Linux and to repair Linux.

### Kali Linux :male_detective:
[Kali Linux](https://www.kali.org/ "official website") is one of the Most Advanced Penetration Testing Distribution.

> for infosec, pentest, forensics, etc.,

### Lubuntu :bird:
[Lubuntu](https://lubuntu.net/ "official website") is a fast and lightweight operating system with a clean and easy-to-use user interface.
It is a Linux system, that uses the minimal desktop LXDE/LXQT, and a selection of light applications.
Because of this, Lubuntu has very low hardware requirements.

> To bring old computer back to life, since it consumes only 350MB of RAM.

### Win10 PE :diamond_shape_with_a_dot_inside:
[Windows PE](https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/winpe-intro "official") (WinPE) for Windows 10 is a small operating system
used to install, deploy, and repair Windows 10 for desktop editions (Home, Pro, Enterprise, and Education), Windows Server, and other Windows operating systems.

Also it can be used as live os.
To create a bootable WinPE USB flash drive, CD, DVD, or virtual hard drive.
[Download this](https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/download-winpe--windows-pe "official")

> for live Windows and to repair Windows.

### Android-x86 :iphone:
[Android-x86](https://www.android-x86.org/ "official website") is a project to port [Android open source project](https://source.android.com/ "official") to x86 platform. (Run Android on your PC)

> for live Android

## Tools

### Super Grub2 Disk :minidisc:
[Super GRUB2 Disk](https://www.supergrubdisk.org/super-grub2-disk/ "official website") helps you to boot into most any Operating System (OS)
even if you cannot boot into it by normal means.

### Rescatux :speedboat:
[Rescatux](https://www.supergrubdisk.org/rescatux/ "official website") is a Debian-based live distribution featuring a graphical wizard
for rescuing broken GNU/Linux and Windows installations and boot loaders.

> To [reset windows password](https://pogostick.net/~pnh/ntpasswd/ "can use this too 'Offline Windows Password & Registry Editor'"), linux password, fix windows bootmgr, etc.,

### ??? :eye:
Hardware Diagnostic tool
> system spec, monitor test, keyboard test, cpu gpu test, etc...

## Storage
Just make a folder 'Storage' with a empty file 'Storage/.ventoyignore',  
now you can put your files, etc., there. :wink:
