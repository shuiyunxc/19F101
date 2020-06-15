



<img src="https://shuiyunxc.gitee.io/images/full-logo-light.svg" alt="full-logo-light" style="zoom:25%;" />

### **【独行秀才】macOS Catalina 10.15.5(19F101)原版镜像 by OpenCore-0.6.0-06-05编译版** 

## 说明

- 本镜像采用Apple App Store下载的官方原版app制作，并集成了OpenCore-0.6.0-06-05编译版，仅支持UFEI启动安装。

- `OpenCore-0.6.0`引导，机型设置为iMac 19.1，适合大多数主板/笔记本安装，个别主板/笔记本微调适合自己主板的机型或SSDT即可。

- 有集显的CPU，安装的时候，建议在BIOS里面关闭集显，安装完成后，后期完善的时候，开启集显（注意BIOS里面是开启，不要设置为自动）。无独显的机器，仅设置`AAPL,ig-platform-id`项，如：`07009B3E`  。其他集显项，待安装完成后，完善。

- 驱动里面，`AppleALC.kext`、`Lilu.kext`、`WhateverGreen.kext`均为最新版。

- 默认CFG Lock已经解锁（0x00），如果未解锁，请参照[OpenCore黑苹果引导配置说明第六版](https://shuiyunxc.gitee.io/2020/03/10/instru/index/)里面勾选相应的选项。

- 添加了[SSDT-PMC](https://shuiyunxc.gitee.io/2020/03/10/instru/index/SSDT-PMC.aml.zip)，模拟了原生nvram，所以非原生nvram的选项未勾选。

- 默认设置开启了启动声音。

- 此镜像独行秀才亲自测试，完成引导-抹盘-完成安装-顺利进到系统。

- 镜像发布站点：[独行秀才的老窝](https://shuiyunxc.gitee.io/)/[CDSDN独行秀才的Blog](https://blog.csdn.net/shuiyunxc)

  

  ## 相关截图

  

  <img src="/Volumes/123/123/macOS Catalina 10.15.5(19F101)/44C651A49.jpg" alt="44C651A49" style="zoom:80%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/71405F64.jpg" alt="71405F64" style="zoom:60%;" />

  

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/AB4C5DA.jpg" alt="AB4C5DA" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/1677AFBE.jpg" alt="1677AFBE" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/DD.jpg" alt="DD" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/6F516F.jpg" alt="6F516F" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/5C376.jpg" alt="5C376" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/CC4F20D.jpg" alt="CC4F20D" style="zoom:55%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/CF0E6E0.jpg" alt="CF0E6E0" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/2282EA04.jpg" alt="2282EA04" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/E471A74E.jpg" alt="E471A74E" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/FA54DFAE1.jpg" alt="FA54DFAE1" style="zoom:53%;" />

  <img src="https://shuiyunxc.gitee.io/2020/04/10/19E287/index/5AC8F64C.jpg" alt="5AC8F64C" style="zoom:53%;" />

  

  ## 下载地址

  百度云：https://pan.baidu.com/s/1kVmzJdTjYXuaxsri4cULjw  密码:ke7f

  天翼云：https://cloud.189.cn/t/IVZbemNbaaM3（访问码：3yol）

  Google云盘：https://drive.google.com/drive/folders/1nYtsZM-WRU94B4fQ2m50VlKCwi9nUBSZ?usp=sharing

  Mega：https://mega.nz/folder/LMwT3T5T#wCKDgzRmm4emcGFwdnWRZg

  下载完成后请校验MD5、SHA1与SHA256，确认一致，否则重新下载！

  MD5：5b18e0dfd68c817f3ddeed8261967311

  SHA1：73ff97bd43c97a7620f880f17d79864e89e2bb00

  SHA256：5688e2f1ce82bd000ba1184659e6127ec1269668e63701731d23307912d2cd3b

  终端输入：openssl md5 拖入镜像

  终端输入：openssl sha1 拖入镜像
  
  终端输入：openssl dgst -sha256 拖入镜像
  
  Windows下的验证请自行搜索

#### 重要声明：独行秀才拥有此篇文字与图片所有版权，严禁用于任何商业用途，否则将追究法律责任！不建议在远景论坛转载，大概率会被远景封号，谢谢合作！！

<img src="https://img.shields.io/badge/更新日期：-2020年04月10日-red?style=flat-square" align='center'>


