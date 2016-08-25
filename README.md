#This is a berserk kernel for ARK Benefit A3(peach)
 This is a rebase kernel from Wingtech WT88047

Working:
- Start
- LCD Panel
- Touch Panel
- RIL
- Charging
- Camera(full work)
- USB Connecting
- Radio
- Wi-Fi
- GPS
- Autorotaion
- Autobrightness sensor
- Proximity sensor
- Mobile data
... More

Not work/Bugs:
- Nothing

Compilation:

    export ARCH=arm
    export CROSS_COMPILE=/path_to_your_toolchain/
    make cyanogenmod_peach_defconfig
    make zImage-dtb
Check arch/arm/boot/ folder
