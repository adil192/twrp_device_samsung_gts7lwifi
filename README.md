## Recovery Device Tree for the Samsung Galaxy Tab S7 Wi-Fi (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_gts7lwifi-eng
make recoveryimage
```

Kernel source:
https://github.com/adil192/twrp_kernel_samsung_sm8250
