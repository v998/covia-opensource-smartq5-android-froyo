# Covia SmartQ5 Android 2.2 froyo official OpenSource Project #

This is Covia Android 2.2 for [SmartQ5](http://www.covia.net/main/product-smartq5.html) opensource project.

We'd appreciate any contribute for the SmartQ5 android 2.2.

Quick Rebuild HOWTO:
```
Howto Create Covia Smartq5 2.2 froyo firmware from scratch.

build env: Debian 6.0 (squeeze)

#mkdir opensource-smartq5
#cd opensource-smartq5  
#repo init -u git://gitorious.org/covia-android-2-2/nami_smartq5_manifests.git  
#repo sync  
#source myenv  
#make  
#sudo ./buildfs.sh

it will create a file called “SmartQ5”
put this file to your SDCARD and press power and [+] to upgrade
```

Latest Firmware: (2011-02-24)
http://covia-opensource-smartq5-android-froyo.googlecode.com/files/SmartQ5

Latest Firmware md5sum:
fecb33e11b0a56130c4e35664cf32eff  SmartQ5 (2011-02-24)

Upgrade Howto:
put SmartQ5 to your SDCARD vfat partition and press power and [+] to upgrade.