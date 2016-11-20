Local manifest for CyanogenMod 14.1 TWRP Recovery
==============

To add this CAF-powered manifest to your local repository, use this command in source's root:

    git clone git://github.com/CastagnaIT/local_manifests.git -b cm-14.1_twrp .repo/local_manifests
    

Then to sync up:

    repo sync


To build:

    source build/envsetup.sh
    lunch cm_ks01lte-eng
    make -j12 recoveryimage
