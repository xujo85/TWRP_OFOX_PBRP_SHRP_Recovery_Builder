# Recovery Builder for |TWRP / PBRP / OFRP / SHRP|
Compile your first custom recovery via Github Actions - with ldcheck setup.

This repo comes from a long chain of forks and finally ended up with working shrp and some revamping of the workflow files.

If there are any issues relating the build tree info (not the workflow file config entries), feel free to open a pull request.

## How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > Pick which Build you need (`TWRP or PBRP or OFRP or SHRP`) > `Run workflow`, then pick required information from each drop-down list:
 - Manifest Branch (*12.1, *11.0, *10.0, *9.0, *8.1, *7.1, *6.0, etc.)
 - Device Tree (Your device tree repository link)
 - Device Tree Branch (Your device tree repository branch)
 - Build Target (boot, reecovery, vendorboot)
 - LDCHECK (path to your target binary file, ie. `system/bin/qseecomd`)
   - If you are building manually/locally and you want to use ldcheck for checking dependencies, visit [THIS](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) this for guide.

## Thanks/Credits
 - [CaptainThrowback](https://github.com/CaptainThrowback)
 - [azwhikaru](https://github.com/azwhikaru)
 - [cd-Crypton](https://github.com/cd-Crypton)
 - [that1](https://github.com/that1)
 - [carlodandan](https://github.com/carlodandan)
 - And to all Contributors in every repositories and scripts I used.
 - [Recovery builder (derived from) and lazycodebuilder](https://github.com/lazycodebuilder/Lazy_Action-Recoverys-Builder)
