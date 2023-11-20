## Recovery Device Tree for the Samsung Galaxy S9+ (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_star2qlte-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_sdm845
