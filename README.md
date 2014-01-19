slimkat_manifest
================

Local Manifest to build SlimKat for the Huawei Y300 & G510

Build Instructions for SlimKat Y300 (U8833)  & G510 (U8951)
-----------------------------------------------------------------------------

1. Initialize repo using the SlimKat manifest (CAF branch)
    
        repo init -u git://github.com/SlimRoms/platform_manifest.git -b kk4.4-caf

2. Add my local manifest

        mkdir .repo/local_manifests
        Copy slimkat_huawei.xml to .repo/local_manifests

3. Then sync up the repositories
 
        repo sync

4. Initialize the build environment

        source build/envsetup.sh
    
5. Build the ROM

        For Y300:
            brunch u8833
        For G510:
            brunch u8833
