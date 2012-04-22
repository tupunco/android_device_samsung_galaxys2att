Device configuration for the Samsung Galaxys2ATT (I777)
------------------------------------------------------------------------------

base [https://github.com/CyanogenMod/android_device_samsung_galaxys2/tree/ics]()

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

----------------------

How To Build CM9 for Samsung Galaxys2ATT
=========================

Do repo init & sync CM9

            https://github.com/CyanogenMod/android

local_manifest.xml add

            <project path="device/samsung/galaxys2" name="CyanogenMod/android_device_samsung_galaxys2" />
            <project path="device/samsung/galaxys2att" name="tupunco/android_device_samsung_galaxys2att" />

repo sync

Setup device

            cd CM9_SRC_DIR/device/samsung/galaxys2att
            ./extract-files.sh

build CM9

            cd CM9_SRC_DIR
            . build/envsetup.sh 
            lunch cm_galaxys2att-userdebug
            make -j4 otapackage

Thanks

   [teamhacksung](https://github.com/teamhacksung)
   CyanogenMod team



----
EOF
