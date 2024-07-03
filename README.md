# TWRP & OrangeFox Device Tree for Samsung Galaxy Tab S9 Ultra

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/android_device_samsung_gts9u device/samsung/gts9u
```

## Kernel version 
```
5.15.123-Archer3770-Kernel (Current)
```

## Kernel source 
```
https://github.com/edward0181/android_kernel_samsung_sm8550
```

## To build
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_gts9u-eng
mka recoveryimage
```
