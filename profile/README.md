# 🔥 Samsung Exynos 7420 Organization 🔥
The (un)official Samsung Exynos 7420 GitHub organization. Attempting to tame and update the 7420 since 2022.

Currently supporting Lineage 18.1, Lineage 19.1 and Lineage 20 (not other AOSP/forks). You can find a sample local_manifest here: <https://github.com/samsungexynos7420/local_manifests>

Building LineageOS 19.1 or later requires patching the sources in order to get boot and some functions working properly. All the patches that are needed for this are located at <https://github.com/samsungexynos7420/7420_patches> and **MUST** be applied. 

# Currently supported devices:
- Samsung Galaxy S6 (International, TMobile, Canada)
- Samsung Galaxy S6 Edge (International, TMobile, Canada)
- Samsung Galaxy S6 Edge+ (International, TMobile, Canada)
- Samsung Galaxy Note5 (International, TMobile, Canada)

# Untested/TODO
- Samsung Galaxy A8 2016
- Samsung W2016

# Supported OSes
- Lineage 18.1 (A11)
- Lineage 19.1 (A12L)
- Lineage 20.0 (A13)

# Have some improvement you want to add?
Open a pull request and I will look at it. Any help is welcome as long as it isn't malicious or could break things. 

# TODO:
## Kernel
- Implement cgroup v2 
- Update sched and implement EAS
- Update throttling/hotplug behaviour
- Fix broken endianness regmap in audio drivers
- Add VDSO32
- Add working aio f_fs

## Other stuff
- Fix virtualdisplay compilation
- Build Camera HAL and dependancies from source
- Fix NFC not initialising properly after restarting when turned off
- Better auto brightness
- Fix libsensor shim
- Patches for Lineage 21 
