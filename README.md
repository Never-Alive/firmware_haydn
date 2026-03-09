# android_vendor_xiaomi_haydn-firmware

Firmware images for Mi 11i (haydn), to include in custom ROM builds.

**Current version**: fw_haydn_miui_HAYDNGlobal_OS1.0.18.0.UKKMIXM_8c94291f65_14.0

### How to use?

1. Clone this repo to `vendor/xiaomi/haydn-firmware`

2. Include it from `BoardConfig.mk` in device tree:

```
# Firmware
-include vendor/xiaomi/haydn-firmware/BoardConfigVendor.mk
```
