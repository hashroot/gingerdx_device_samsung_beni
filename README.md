android_device_samsung_beni
==========================

Device configuration for Samsung beni GT-S5670 for compiling GingerDX

Getting Started
---------------

To get started with Android for ARMv6/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/Teamfun/android.git -b gingerbread

Then to sync up:

    repo sync

Build your device:

    source build/envsetup.sh
    brunch beni

Flash ZIP:

    out/target/product/beni/cm-VERSION-DEVICENAME.zip


Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

For more information on this Github Organization and how it is structured,
please [read the wiki article](http://wiki.cyanogenmod.org/index.php/Github_Organization)

