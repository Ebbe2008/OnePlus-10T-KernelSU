## NO LONGER ACTIVE, i've sold the device.

# OnePlus-10T-KernelSU
Images made by yours truly for installing KernelSU for OnePlus 10T devices
There are both india and Eu boot images in releases
I'll try to keep this up to date but i still have to do my daily tasks before that

# Requirements
- Unlocked bootloader
- ADB And Fastboot

# Flashing steps
- when booted into os connect to pc then run:
```
adb reboot bootloader
```
```
fastboot boot <patched-boot.img>
```
IF it boots succesfully
```
adb reboot bootloader
```
```
fastboot flash boot <patched-boot.img>
```
```
fastboot reboot
```

You probably don't care but here's my paypal anyways feel free to donate if you want to:

`
@EbbeChr
`
