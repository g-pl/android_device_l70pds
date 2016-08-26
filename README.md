CyanogenMod 13.0 device configuration for LG L Fino l70pds (D295)


How to build:
-------------

Initializing a Build Environment:

    https://source.android.com/source/initializing.html

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-13.0

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/geekydoc/android_local_manifest/cm-13.0/local_manifest.xml
    
    repo sync

Compile:

    . build/envsetup.sh
    brunch cm_l70pds-userdebug
