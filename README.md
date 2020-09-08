## Install Google Pinyin input on Ubuntu 18.04

https://leimao.github.io/blog/Ubuntu-Gaming-Chinese-Input/

Hotkey: ctrl + space for toggling between English and Chinese input.


## Dell G3 laptop recovery for Windows  10
I accidently messed up BIOS, and it didn't boot anymore. After unsuccessfully trying some boot-repair tricks, I decided to reinstall system. Here are the steps for recovering Windows 10 on Dell G3 laptop:
* Reboot computer, and keep tapping F12 to go to BIOS menu
* Select 'Dell Support Recovery Assitant', then select 'Recovery from Cloud' (I tried 'recovery from local', it finished without error but still didn't boot.)
* Then it tried to install Windows 10 from cloud, and restarted a couple times. It came to a stage where it shows both admin and default0 user, which both require password. Select 'reset PC' to remove personal info, and reinstallation started.

## Install Ubuntu 20.04 along with Windows 10 on Dell G3 laptop
After I recovered Windows 10 on my Dell G3 laptop, I installed Ubuntu 20.04 as dual boot in the following steps:
* Download Ubuntu 20.04 .iso file from its official website
* Download SD card formatter from sdcard.org to format USB stick
* Download Rufus to create bootable Ubuntu stick, where partition scheme is MBR.
* On windows, open disk management, shrink C drive with certain size, e.g. 100GB for Ubuntu.
* On windows, open system, check BIOS mode, mine is uefi.
* Reboot computer, keep tapping F12 to go to BIOS menu, highlight 'boot from USB with uefi'. Note: 1) don't use 'boot from USB with legacy', 2) may need to go to BIOS Setup to change setting. 
* Then you will see the Ubuntu grub menu, and start installation.


