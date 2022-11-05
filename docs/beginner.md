# 新手使用指南
```
三千预算进卡吧，加钱加到九万八。十核E7装上去，四路泰坦抱回家。  
4K屏幕组三屏，万元水冷温度压。固态硬盘装三块，硬盘内存使劲加。  
键鼠必花几千块，耳机手柄八千八。还有机箱一万一，红星炸弹啪啪啪。  
最后发现没啥用，抱着神机刷贴吧。   

三千预算进图吧，学校对面开网吧。AN矿卡是标配，垃圾靠岸笑哈哈。  
坏道迈拓装系统，并口硬盘论车拉。老式志强超频爽，奔腾菜羊够用啦。  
十手矿卡装上去，鱼竿内存满箱插。机箱路边随便捡，安踏鞋盒擦一擦。  
机械键盘自己搞，鼠标一斤一块八。人人手拿七七五，家家双路叉五八。  
萝卜散热效果好，牙膏硅脂温度压。二手便宜质量好，一切信仰就是渣。  

——大人，时代变了，好好装机！本教程面向Windows平台。  
```

## 1、Windows 系统安装

### （1）准备工作
（A）一个U盘（≥8GB），存放安装镜像  
（B）一个联网、可以读写USB的电脑或手机  
（C）一个准备安装系统的PC 

### （2） 创建引导U盘
#### 方法一、官方工具全自动创建

1、下载镜像生成工具：  
Windows 10：[https://www.microsoft.com/zh-cn/software-download/windows10](https://www.microsoft.com/zh-cn/software-download/windows10)  
Windows 11：[https://www.microsoft.com/zh-cn/software-download/windows11](https://www.microsoft.com/zh-cn/software-download/windows11)

![image-20221105195847471](imgs/image-20221105195847471.png)

2、插入U盘，打开MediaCreationToolxxxx.exe。选择创建安装介质。

![image-20221105200048764](imgs/image-20221105200048764.png)

3、版本选择Windows 10 / Windows 11，默认包含全版本安装文件。体系一般为x64。

![image-20221105200243172](imgs/image-20221105200243172.png)

4、选择创建方式。推荐选择**U盘**，一步到位。若需单独使用iso镜像，则选择**ISO文件**。

![image-20221105200447557](imgs/image-20221105200447557.png)

5、点击下一步（ISO方式记住保存路径，按方法二/三/四继续操作），等待创建完成。

![image-20221105201129151](imgs/image-20221105201129151.png)

#### 方法二、手动下载镜像解压

1、准备ISO镜像，使用上方工具创建ISO文件，或从Next,ITellYou网站下载，点击[NEXT, ITELLYOU](https://next.itellyou.cn/)。

![image-20221105204359769](imgs/image-20221105204359769.png)

2、下载选择商业版/business版，后续适用各种激活方式。复制ED2K或BT自行下载。

![image-20221105204822477](imgs/image-20221105204822477.png)

3、下载镜像后解压镜像内文件至U盘根目录。U盘格式推荐为FAT32，兼容性最佳。解压完成即可引导安装。

![image-20221105205048187](imgs/image-20221105205048187.png)

#### 方法三、Rufus写入U盘

1、准备ISO镜像，方法如上。

2、下载Rufus（图吧工具箱内置，其他工具-Rufus），[点此手动下载3.20版本](https://github.com/pbatard/rufus/releases/download/v3.20/rufus-3.20.exe)。

3、插入U盘，打开Rufus，选择镜像。  
* 不支持EFI引导的平台分区类型选择MBR，否则保持默认。  
* 固态U盘、移动硬盘需启用**显示USB外置硬盘选项**。  
* 文件系统选择FAT32以保持最大兼容。   

![image-20221105210210126](imgs/image-20221105210210126.png)

4、点击开始按钮，安装弹窗按需选择。等待镜像写入完成。

![image-20221105210839059](imgs/image-20221105210839059.png)

#### 方法四、PE类工具安装

1、下载PE，推荐[WePE](https://mirrors.sdu.edu.cn/software/Windows/WePE/WePE64_V2.2.exe)，插入U盘创建启动盘。

2、准备ISO镜像，无需解压直接拷入**微PE工具箱**分区。

### （3）引导启动安装镜像

### （4）可选：注入驱动



