# OnePlus-10T-KernelSU
Images made by yours truly for installing KernelSU for OnePlus 10T devices 

# Requirements
- Unlocked bootloader
- ADB And Fastboot

# Flashing steps
- when booted into os connect to pc then run:
`
adb reboot bootloader
`
`
fastboot flash patched-boot.img
`
`
fastboot reboot
`
