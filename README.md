# Woods-TWRP
TWRP for woods
Team Win strives to provide a quality product. However, it is your decision to install our software on your device. Team Win takes no responsibility for any damage that may occur from installing or using TWRP.

We recommend downloading the latest version of TWRP for your device.

Sometimes, firmware updates for a device break compatibility. If you have not updated the firmware on your device and the latest version of TWRP is not working for you, you may want to try an older version.

Downloading an image for a different device, no matter how similar, usually does not work.
. The full changelog

5G
OnePlus 6T
Win a Mi 9
Honor View20
Honor Hub
Android Q
Galaxy Note 9
LG V40
Snapdragon 855
Pixel 3

TWRP 3.3.1+ will no longer require installer ZIPs, adds a reboot to EDL mode button, and more

TWRP 3.3.1+ will no longer require installer ZIPs, adds a reboot to EDL mode button, and more
For most users, installing any kind of after-market software modification, whether it be a custom ROM, custom kernel, or other tool, requires the use of a custom recovery like TWRP. TWRP has been around for years as the go-to recovery solution for the XDA community. It’s open source and supports hundreds of devices. It offers features like full backup and restore, ADB sideloading, and much more. Today, the project has been bumped to version 3.3.1-0, bringing many improvements in decryption, new features, and a major change to the way TWRP is installed.

The full changelog outlining the many improvements in TWRP’s decryption support can be found below, but for users, the most important change will be the new way to install the custom recovery. Currently, installing TWRP on a device with A/B partitions requires booting TWRP temporarily and then installing it permanently using an installer script. Going forward, users will be presented with a new “install recovery ramdisk” option in recovery. This means that users can boot TWRP and then install it without downloading a separate ZIP file. XDA Senior Recognized Developer Dees_Troy worked with XDA Recognized Developer topjohnwu to make this possible by adapting Magisk‘s boot image patching for TWRP. Dees_Troy says the team will offer installer ZIPs this time around to give people a chance to update from older versions, but future TWRP releases won’t have separate installer scripts.

The other change that’s most relevant to users is the inclusion of a “reboot to EDL mode” button. Emergency Download mode can help you fully unbrick a device if you have the right tool, but the button combination to enter it isn’t as well known to users as the reboot to recovery method.

Here’s the full changelog for the update:

TWRP 3.4.0-0 Changelog

Merge AOSP 9.0 r3 (Dees_Troy)
Use ANDROID_ROOT variable instead of hard coding to /system (CaptainThrowback)
Decrypt FBE on 9.0 and metadata decrypt (Dees_Troy)
vold decrypt updates (CaptainThrowback and nijel8)
Support vibration on LED class devices (notsyncing)
Metadata decrypt support for Pixel 3 (Dees_Troy)
Support rotating the display via build flag (vladimiroltean)
Reboot to EDL mode button (mauronofrio)
Support MTP on FFS devices (bigbiff)
Update FDE decrypt to support keymaster 3 and 4 (Dees_Troy)
Detect mkfs.f2fs version to properly format on f2fs partitions (Dees_Troy)
Allow TWRP to use md5 and sha256 checksums for zip installs (bigbiff)
TWRP can use /data/cache/recovery and /persist/cache/recovery on AB devices with no cache partition (bigbiff)
Switch part of advanced menus in TWRP to use a listbox of options (Dees_Troy)
Use magiskboot to allow repacking boot images for installing TWRP
Developers behind (Dees_Troy with thanks to topjohnwu of course)

Updated 3.4.0-0 TWRP
