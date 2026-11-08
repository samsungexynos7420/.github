# 🔥 Samsung Exynos 7420 Organization 🔥
The (un)official Samsung Exynos 7420 GitHub organization. Attempting to tame and update the 7420 since 2022.

Currently supporting LineageOS (not other AOSP/forks). You can find a sample local_manifest here: <https://github.com/samsungexynos7420/local_manifests>

Building requires patching the sources in order to get some functions working properly and **MUST** be applied. All the patches that are needed for this are located at <https://github.com/samsungexynos7420/7420_patches>  

# Currently supported devices:
- Samsung Galaxy S6 (International, TMobile, Canada)
- Samsung Galaxy S6 Edge (International, TMobile, Canada)
- Samsung Galaxy S6 Edge+ (International, TMobile, Canada)
- Samsung Galaxy Note5 (International, TMobile, Canada)

# Untested/TODO
- Samsung Galaxy A8 2016
- Samsung W2016

# Supported OSes
- crDroid 7 (A11)
- Lineage 18.1 (A11)
- Lineage 19.1 (A12L)
- Lineage 20.0 (A13)
- Lineage 21.0 (A14)

# Have some improvement you want to add?
Open a pull request and I will look at it. Any help is welcome as long as it isn't malicious or could break things. 

# TODO:
## Kernel
- Implement EAS
- Fix broken endianness regmap in audio drivers
- Add VDSO32/timers
- Move away from plat/mach

## Other stuff
- Fix virtualdisplay compilation
- Build Camera HAL and dependencies from source
- Better auto brightness
