## MacOS Catalina 10.15.5(19F101)

# # instructions

- This image is made from the original official App downloaded from Apple App Store and integrated with OpenCore 0.6.0-06-05, which only supports UFEI startup and installation.
- 'OpenCore-0.6.0' boot, model set to iMac 19.1, suitable for most motherboards/laptops installation, a few motherboards/laptops fine tuning for their own motherboards or SSDT can be.
- For cpus with set display, it is recommended to turn off the set display in the BIOS during installation, and turn on the set display after installation (note that the BIOS is on, do not set it to automatic). Only 'AAPL, IG-platform-ID' items are set, such as: '07009B3E'. Other display items, to be installed after completion, improve.
- In the driver, 'applealc.kext', 'lilu.kext', 'WhateverGreen'. Kext 'are all the latest versions.
- the default CFG Lock is unlocked (0 x00), if you do not unlock, please refer to [OpenCore black apple lead configuration instructions sixth edition] (https://shuiyunxc.gitee.io/2020/03/10/instru/index/) check the corresponding option.
- added [SSDT - PMC] (https://shuiyunxc.gitee.io/2020/03/10/instru/index/SSDT-PMC.aml.zip), to simulate the native nvram, so the non-native nvram option is not checked.
- The default setting turns the boot sound on.
- This image is tested by a solo tester, complete boot - wipe - complete installation - smooth entry into the system.

Baidu cloud: https://pan.baidu.com/s/1kVmzJdTjYXuaxsri4cULjw password: ke7f

Physical cloud: https://cloud.189.cn/t/IVZbemNbaaM3  access code:(3yol)

Google cloud disk: https://drive.google.com/drive/folders/1nYtsZM-WRU94B4fQ2m50VlKCwi9nUBSZ?usp=sharing

Mega: https://mega.nz/folder/LMwT3T5T#wCKDgzRmm4emcGFwdnWRZg

After downloading, please check MD5, SHA1 and SHA256 to make sure they are consistent, or download again!

MD5:5 b18e0dfd68c817f3ddeed8261967311

SHA1:73 ff97bd43c97a7620f880f17d79864e89e2bb00

SHA256:5688 e2f1ce82bd000ba1184659e6127ec1269668e63701731d23307912d2cd3b

Terminal input: OpensSL MD5 drag in the mirror

Terminal input: OpensSL Sha1 drag in mirror

Terminal input: OpensSL DGST-SHA256 drag into mirror
