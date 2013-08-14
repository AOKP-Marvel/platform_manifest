platform_manifest
=================
Android for Samsung Ace (cooper)

$ repo init -u git://github.com/AOKP-Marvel/platform_manifest.git -b AOKP-legacy

$ repo sync

$ source build/envsetup.sh

$ lunch aokp_marvel-userdebug

$ make -j(number of cores *2)

This isn't ready to compile for marvel
