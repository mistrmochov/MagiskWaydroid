# magiskWaydroid
Small and quick scripts, that puts finished magisk files to waydroid directory. Fully working Magisk Delta!!

![installedmagisk](https://magiskwaydroid.fra1.digitaloceanspaces.com/magiskimage.png)

**Purpose of this script.**

 Use this scripts if the script from nitanmarcel doesn't work. This script copies "preinstalled" magisk to your waydroid directory. These files are generated from the script, that I mentioned before,I managed to rescue these files from my old HDD
 and I made script based on this so others can benefit. 
 Note: With this script you get only one version of Magisk, which is Magisk Delta 26.3 (Not Kitsune Mask). Magisk Delta fully works and you can install all the sweet stuff and modules you want.

 **Requirements**

 waydroid
 git
 tar
 gzip

 **Install instructions**
 
 First please make sure, that your Waydroid is installed and initialized!

 If you have been installing magisk from nitanmarcel script, make sure you run: "sudo waydroid_magisk remove", before installing this script! Althought, now this script should remove all conflicting files.
 ```shell
git clone https://github.com/mistrmochov/magiskWaydroid
chmod +x magiskinstall.sh
./magiskinstall.sh (DO NOT RUN AS ROOT OR SUDO, or it wont work, but when you are prompted for sudo password put it there of course!)
```
 then press y and you're done
 
 For removal use magiskremove.sh
 
 With magisk installed, Waydroid usually boots longer and in first boot after you install magisk, It can take few seconds untill Magisk manager pops up, So if it's not in the applications, just wait.
 Also please do not update Magisk or you will lose root.
 
 **Compatibility**
 
 These files are for x86_64 architecture, so for arm It propably won't work.
 
 If you're using Archlinux based distros you need linux-xanmod-anbox kernel and its header!

