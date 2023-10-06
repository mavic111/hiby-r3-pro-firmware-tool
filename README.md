# hiby-r3-pro-firmware-tool

Tool for modifying Hiby R3 Pro firmware

## Unpack Firmware

Double click on `unpack.bat`

There will be system folder after unpack.

## Modify Firmware UI

For modifying the boot animation, go to `/system/usr/resource/litegui/boot_animation`

For modifying shutdown animation, go to `/system/usr/resource/litegui/shutdown_animation`

For modifying theme 1, go to `/system/usr/resource/litegui/theme1`

For modifying theme 2, go to `/system/usr/resource/litegui/theme2`

For modifying fonts, go to `/system/usr/resource/fonts`

## Pack Firmware

Double click on `pack.bat`

It will creating firmware .upt file.

## Install Firmware

Copy the .upt file to Hiby R3 Pro storage, then install it from System settings > Firmware update > Via SD-card.
