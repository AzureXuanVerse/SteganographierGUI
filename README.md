# SteganographierGUI
将文件隐写进MP4/MKV文件中

请确保在理解“**后缀名**”这个词含义的前提下观看以下教程，如不理解，请首先搜索“[**如何改后缀名**](https://cn.bing.com/search?q=%E5%A6%82%E4%BD%95%E6%94%B9%E6%96%87%E4%BB%B6%E5%90%8E%E7%BC%80%E5%90%8D)”

如果改了后缀还是为 MP4 ，那说明没有开启后缀名显示，请依然搜索上述内容

解压不了(|怎么是视频|密码错误|文件损坏|需要分卷|等)

**改 MP4 后缀为 .zip 用** [**WinRAR**](https://wwmh.lanzoul.com/b004i2rjbi?pwd=c9ar) **解压**

**改 MP4 后缀为 .zip 用** [**WinRAR**](https://wwmh.lanzoul.com/b004i2rjbi?pwd=c9ar) **解压**

**改 MP4 后缀为 .zip 用** [**WinRAR**](https://wwmh.lanzoul.com/b004i2rjbi?pwd=c9ar) **解压**

WinRAR分享提取码c9ar

**其他解除隐写方法（根据自己所用的解压软件对号入座）**

**1.** [**WinRAR6**](https://wwmh.lanzoul.com/b004i2rjbi?pwd=c9ar)  (提取码c9ar)**（注意不能是WinRAR5）：**

   1.1. 对于 MP4 隐写文件，直接改后缀名为 **.zip** 即可解压（必须是 **zip**，不是 rar 也不是 7z 或者别的）
   1.2. 对于 MKV 隐写文件，改后缀名后，【工具-修复压缩文件】，然后再解压。

![117c966dac71fd2b968b0b31bd6f2551.webp](https://file.cangku.moe/images/117c966dac71fd2b968b0b31bd6f2551.webp)

  

**2.** [**7-zip**](https://sparanoid.com/lab/7z/)**：**

   2.1. MP4隐写文件先修改后缀名，然后右键点击文件，用 **#号模式** 打开压缩包，解压 **2.zip** 即可，如下图：

![fac85bc467296f3e462e8389413be4ec.webp](https://file.cangku.moe/images/fac85bc467296f3e462e8389413be4ec.webp)

![e2980c285a62a1bdb438f36b14c9374b.webp](https://file.cangku.moe/images/e2980c285a62a1bdb438f36b14c9374b.webp)

    2.2. MKV隐写文件同上，用 **#号模式** 打开压缩包，即可解压。
    2.3 使用命令行解压（-i!*.zip 表示仅解压.zip部分，通过此法解压出的压缩包文件名为 "2.zip"）

windows
```
7z x -t# "D:\TEMP\测试_hidden.mp4" -o"D:\TEMP" -i!*.zip
```

linux
```
7za x -t# "/tmp/测试_hidden.mp4" -o"/tmp" -i'!*.zip'
```
[下载地址](https://sparanoid.com/lab/7z/)

注：7zip 及 Bandizip 不能解压使用汉字作为密码的隐写文件（WinRAR 可以），如果仍想解压需要一些操作，请参考下面的内容

[collapse title="bandizip 和 7zip 解压用中文密码隐写文件的方法"]

因为编码问题，bandizip 和 7zip 不能直接解压用汉字做密码的隐写文件，因为汉字用了 GBK 编码。而解压时，这 2 个解压软件默认用的是 UFT-8 编码，编码方法不一样所以会报密码错误。  
  
但是仍然有一种办法可以得到正确的密码，如前所述，错误的原因是 bandizip 和 7zip 解码只认 UTF-8，所以只需要把 GBK 下密码强行用 UTF-8 进行编码就可以了，这样解密的时候能保证编解码匹配。  
  
比如密码为：某不知名网友分享  
用 UTF-8 强行编码的结果为：鏌愪笉鐭ュ悕缃戝弸鍒嗕韩  
  
用这个看似乱码的密码去解压就可以了。  
  
可以在这个网址【請輸入亂碼文字：】输入汉字，然后转换为 utf-8  
[https://www.ifreesite.com/textconvert.htm](https://www.ifreesite.com/textconvert.htm)

![](https://file.cangku.moe/images/bcaea65da35eee77ba4bb6db081a3946.webp)

如果使用 notepad++ 也可以使用编码转换功能，如下图  

![](https://file.cangku.moe/images/9b481fda64754402f8271d7f1cad143c.webp)  

[/collapse]


**3.** [**Bandizip**](https://wwmh.lanzoul.com/b004i2rk4h?pwd=5avf)：

实测 **7.36 版本以上**的 Bandizip 直接修改两种隐写文件后缀即可解压（较低版本解压会提示需要分卷），[下载地址](https://wwmh.lanzoul.com/b004i2rk4h?pwd=5avf) 提取码5avf

注：7zip 及 Bandizip 不能直接解压使用汉字作为密码的隐写文件（WinRAR 可以），如果仍想解压需要一些操作。

因为编码问题，bandizip 和 7zip 不能直接解压用汉字做密码的隐写文件，因为汉字用了 GBK 编码。而解压时，这 2 个解压软件默认用的是 UFT-8 编码，编码方法不一样所以会报密码错误。

Bandizip 可以在代码页面修改编码方式为 UTF-8 来解决，如下图：

![PixPin_2025-05-30_00-08-15.jpg](https://pic.cangku.moe/images/2025/06/15/1crQh.jpg)


更多方法请参考 7-zip 部分的内容


**4. 手机**：

   **4.1. 【安卓】RAR**：用法和WinRAR相同，[下载地址](https://apkpure.com/rar-extractor-manager/com.rarlab.rar/download/7.01.build123)
   **4.2.** **【苹果】解压专家**：用法和WinRAR相同：[下载地址](https://apps.apple.com/cn/app/%E8%A7%A3%E5%8E%8B%E4%B8%93%E5%AE%B6-dzip-zip-rar-7z-%E5%BF%AB%E9%80%9F%E8%A7%A3%E5%8E%8B%E5%92%8C%E5%8E%8B%E7%BC%A9/id1400133654)


**5. 其余解压软件正在测试中，暂时未找到100%稳定的方法**

   5.1 **zarchiver**：修改后缀为zip后可以解压 MKV 隐写文件，但是无法解压 MP4 隐写文件

  
**6**. 尝试以上方法都无法解压，也可以采用本程序的解除隐写功能解压。


## 更新

**2025/06/28 更新 1.3.1 版本**

新增工作模式 mp4(zarchiver) ，此模式生成的隐写文件可以被 zarchiver 及 [解TMD压](https://cangku.moe/archives/216302) 等从开头扫描压缩文件的解压软件解压，但是无法被从尾部扫描压缩包的 WinRAR 解压，可根据情况使用。

---

### 隐写者 GUI&CLI两用的MP4/MKV隐写程序

作者： 层林尽染



#### 使用说明

本程序可以将文件或文件夹隐写到视频文件中，或从视频文件中提取隐写的文件或文件夹。程序支持命令行界面 (CLI) 和图形用户界面 (GUI) 两种模式。

1. **GUI** 模式： 【推荐】双击直接运行程序，不带任何参数。关于GUI的用法详见[演示视频](https://youtu.be/ztjKF8FPIM0?si=rI4QANcmoU2cQEHn)。

2. **CLI** 模式： 使用以下参数运行程序：

   ```
   -i, --input     指定输入文件或文件夹的路径。如果不使用任何参数标签，程序会将第一个未知参数视为输入路径。
   -o, --output    1. 指定输出文件名(包含后缀名) [或] 2. 指定输出路径(默认为原文件名+"_hidden.mp4/mkv")。
   -p, --password  设置密码 (不指定则无密码)。
   -t, --type      设置输出文件类型 (默认为mp4)，支持mp4和mkv两种格式。
   -c, --cover     指定外壳MP4视频（如果不指定，程序会按照以下顺序搜索：
                      - 程序同目录下的cover_video文件夹下
                      - 程序所在目录下
                      - 输入文件或目录的所在目录下）
   -r, --reveal    执行解除隐写 (如果输入文件不是隐写文件则不进行任何操作)
   ```



#### 使用示例

1. 隐写文件：

   ```
   python Steganographier.py -i "input.txt" -o "output.mp4" -p "password" -t "mp4" -c "cover.mp4"
   python Steganographier.py -i "input.txt" -o "outputFolder" -p "password" -t "mp4" -c "cover.mp4"
   ```

2. 隐写文件夹：

   ```
   python Steganographier.py -i "inputFolder" -o "outputFolder" -p "password" -t "mp4"
   python Steganographier.py -i "inputFolder" -o "output.mp4" -p "password" -t "mp4"
   ```

3. 解除隐写提取文件：

   ```
   python Steganographier.py -i "input.mp4" -r -p "password"
   ```

4. 若仅指定输入文件，则使用默认设置：

   ```
   python Steganographier.py "input.txt"
   ```





#### 注意事项

1. 如果没有指定输出文件路径，程序会在输入文件同目录下创建默认的输出文件，文件名为原文件名 + `_hidden.mp4/mkv`。
2. 如果指定了输出路径但没有指定文件名，程序会在指定输出路径下创建一个默认的输出文件，文件名为原文件名 + `_hidden.mp4/mkv`。
3. 如果输入路径是一个文件夹，程序将隐写整个文件夹。
4. 如果没有指定外壳MP4视频，程序会按照以下顺序搜索：
   - 程序同路径下的 `cover_video` 文件夹
   - 程序所在目录
   - 输入文件或目录的父目录
5. 程序会在程序同路径下查找 `cover_video` 文件夹。如果该文件夹存在，程序会在其中搜索 .mp4 文件。如果该文件夹不存在，程序会跳过这一步，继续在其他位置搜索。
6. 解除隐写时，如果输入文件不是隐写文件则不进行任何操作。

**Full Changelog**: https://github.com/cenglin123/SteganographierGUI/compare/v1.1.0...v1.1.1

* * *

**v1.2.4 更新**

20241027 更新 v1.2.4 版本

- 去除：去除密码掩蔽，便于查看密码内容；
- 增加：现在程序在关闭时会自动记录使用的配置并保存在程序同目录的 config.json 文件中，下次启动时读取；
- 修复：修复 #4 ，现在程序可以正常解除无密码的隐写。

**v1.2.1 更新**

20240828-v1.2.1 版本：解除隐写逻辑新增密码本功能

**v1.2.0 更新**

20240730-v1.2.0 版本：新增集成隐写者到右键菜单的功能

**v1.1.8 更新**

新增验证码生成器扩展工具

**v1.1.7 更新**

新增文件哈希值修改工具

**v1.1.6 更新**

修改解除隐写的逻辑，提升效率

**v1.1.5 更新**

改善压缩zip文件部分的进度显示逻辑，并且程序增加详细日志窗口，便于问题定位

**v1.1.4 更新**

优化程序在嵌入moov box时的运行逻辑，修正一些bug

**v1.1.3 更新**

修改MP4隐写模式，现在会把zip文件嵌入到外壳MP4文件的 moov box 中而不是贴在MP4文件后面

**v1.1.2 更新**

新增隐写大小-外壳时长不合理提醒

**v1.1.1 更新**

修复BUG


**v1.1.0 版本进位**

新增命令行调用的 CLI 模式, 现在程序可以作为第三方工具被其他程序调用

**v1.0.10 改进：**
```
1. 隐写时会随机插入压缩文件的特征码，进一步增加混淆度  
2. 输出文件名可以选择随机文件名  
3. 外壳文件新增名称排序、随机排序、时长排序选项。
```

**v1.0.9 修改**：参数栏添加【输出名】选项，现在可以选择外壳MP4文件名作为输出文件名

**v1.0.8 改进**：新增外壳MP4文件夹选择功能，现在可以点击【选择文件夹】按钮以自行选择外壳MP4文件夹。

**v1.0.7 改进**：外壳文件菜单中的文件现在会按照时长降序排列

**v1.0.6 修改**：密码获取的逻辑变更，现在可以不指定密码

**v1.0.5 改进**：隐写时文件末尾增加随机字节，以使得每次生成的文件哈希值不同

**v1.0.4 改进**：新增外壳文件选择菜单

**v1.0.3 改进**
```
1. 隐写文件夹时现在会在压缩包内生成同名的文件夹  
2. 修改tools的判断逻辑，如果不使用mkv模式则不会弹出警告  
3. 新增mkv文件隐写大小警告（单个mkv文件不能隐写总量超过2GB的资源）  
4. 修正一些其他bug
```

**v1.0.2 新增** 隐写为mkv文件的逻辑，引入第三方工具用于处理mkv文件

```
.\tools\mkvextract.exe
.\tools\mkvinfo.exe
.\tools\mkvmerge.exe
```

**v1.0.1** 修复了无法隐写ZIP格式文件的bug


## 摘要

为了探索秒传链接失效之后国内网盘资源分享的安全问题，本文推荐了一种以 MP4 文件为外壳的文件隐写方法，并进行了压力测试 ，初步证明了方法的有效性。同时分享了对使用隐写技术时的一些经验和使用建议。通过进一步[控制变量测试](https://bafybeiadpfp7wu6qwmyighdel3qw2eqqqacrmyuxfdwc5u4vwmhiw4mqce.ipfs.dweb.link/) ，探讨了评论区地毯式炸链的机制，得出其原因是恶意举报，证明了隐写文件的优势：①无法在线解压，②违规可申诉。然后讨论了[百度网盘的审核机制以及举报的原理](https://hxcy.top/542211.html)。提出了应对恶意举报的[一些策略](https://hxcy.top/541697.html)。

本程序的代码在 [GitHub](https://github.com/cenglin123/SteganographierGUI) 上开源，大家有任何建议欢迎提 issue。


## 1. 前言

如今，国内各大网盘审查政策日趋严格，分享链接炸链的可能性越来愈大。

传统来说，我们采用**带密码的多层压缩包/分卷压缩包**来应对审查问题。这样的做法非常麻烦，并且当层数多、文件大时，频繁解压对于硬盘的损耗也是难以忽视的。围绕这个问题，过去产生了多种利用网盘特性进行**秒传**的解决方案，但是随着网盘政策的收紧，这些方案大多已经失效或名存实亡 。

秒传方案失效以后，基于国内网盘的资源分享重新回到了加密压缩包的形式，分享者开始不可避免地要和网盘的分享及审核系统打交道，加之举报分享链接的**资源倒卖者 (倒狗)** 横行，炸链又开始频频出现，有时候甚至[**地毯式发生**](https://bafybeiadpfp7wu6qwmyighdel3qw2eqqqacrmyuxfdwc5u4vwmhiw4mqce.ipfs.dweb.link/)，分享环境日趋恶劣 。

综上，这使得研究和开发更加隐蔽、安全的数据传输方法变得尤为重要，在这样的艰难情况下，本文介绍的文件隐写技术有望成为后秒传时代的安全分享新方案。

## 2. 方法介绍：把文件隐写到MP4文件中

本程序受到[仓库文章](https://cangku.moe/archives/211591)（以下简称文章[1]）的启发，利用文件隐写技术来隐藏数据从而绕过常规审查。

隐写技术通过将数据嵌入到其他媒体文件中，使数据的存在对于普通观察者而言不可见，从而实现在不引起注意的情况下进行信息传输。

隐写技术已经有很多先例，传统做法主要有 [**图种**](https://cangku.moe/archives/204982)[X7] ，即把数据嵌入图片中，表面上看起来是一张图片，但修改后缀名后可以解压然后得到隐藏的数据。

图种的原理如下：
```
copy /b "图片.jpg" + "压缩包.zip" "生成目标.jpg"
```

但是这样的做法容易引起怀疑，毕竟一张清晰度分辨率都并不算高的图片居然有几个G，并且还有非常高的下载转存记录，这实在太可疑了[[1]](https://cangku.moe/archives/211591)。

因此，考虑**伪装的有效性**，使用 MP4 文件作为隐写的外壳文件更为合理一些，大视频引起怀疑的可能性显然低于大图片。

我们的目标是通过隐写伪装来**降低可疑度**，从而尽可能以**最低的成本**实现安全分享。因为假如被频繁举报，即使压缩包层数再多，密码再复杂，**在已经被强烈怀疑的情况下大概也回天乏术**。因为对于网盘而言，无法解密又被大量举报的文件最省事的方式就是一刀切判定违规（[参考这个试验[5]](https://bafybeiadpfp7wu6qwmyighdel3qw2eqqqacrmyuxfdwc5u4vwmhiw4mqce.ipfs.dweb.link/)）。

> **自然界最好的防御不是叠甲，而是伪装**。

具体实现方面：将 ZIP 格式的压缩包嵌入到比如海绵宝宝这样的普通 MP4 视频文件中，当文件以 MP4 格式被打开时，只能看到海绵宝宝的视频，看不到 ZIP 部分；而当文件名改为 ZIP 以后，解压软件（如WinRAR）可以寻找到 ZIP 部分进行正常解压。如此实现文件的低成本安全分享。

## 3. 程序功能简介

虽然文章[\[1\]](https://cangku.moe/archives/211591)提供了一个有效的代码实现用于文件隐写，但该方法缺乏一个简单易用的操作界面，这限制了其推广与普及。

本程序在文章[[1]](https://cangku.moe/archives/211591)的基础上进行简化，开发了一个包含图形用户界面（GUI）的隐写程序，使用户能够通过简单的拖放和点击操作完成文件的隐写和解隐写。

2024.4.24 新增：根据文章[[2]](https://cangku.moe/archives/199992)提出的方法，也可以把文件以附件的形式嵌入到MKV文件中，在 v1.0.2 版本中新增了此逻辑。


## 4. GUI设计与功能介绍

本程序允许通过**输入密码**和**拖入文件**的方式来直接进行文件的隐写和解隐写。

程序具有以下特点：

**(1) 一体化**：既可以进行**隐写**，也可以在同一个界面进行**解除隐写**操作，提升了程序的整体效率和便利性。
**(2) 拖放功能**：支持拖放文件或文件夹到指定区域，简化了文件选择的过程。
**(3) 通用性**：产生的隐写 MP4 文件可以**手动**修改后缀名解压，**并不强制要求使用本程序**。
**(4) 密码保护**：**~~必须~~**~~输入密码才能进行隐写或解隐写操作。~~ v1.0.6 版后允许不指定密码。
**(5) CLI 调用：** 可在终端窗口中使用指令操作，或被其他应用作为**第三方程序**调用（1.1.0版本更新）
**(6) 右键菜单集成：可以集成到鼠标右键菜单，以类似常见压缩软件的逻辑进行操作**（1.2.0版本更新）

- 演示视频

  https://youtu.be/ztjKF8FPIM0

- GUI界面

[![](https://file.cangku.moe/images/89a2d5d315fe293ee4dd8f22b4e1dd67.webp)](https://file.cangku.moe/images/89a2d5d315fe293ee4dd8f22b4e1dd67.webp)

- 哈希修改器

哈希修改器的适用场景为**传火、补档** ~~或者传和谐文件到网盘~~ 前处理工作，上传文件之前需要修改哈希值以**防止炸链牵连到原分享文件**。

哈希修改的原理类似于隐写，在文件的后面贴 **1** 个随机字节，使得文件的 **MD5** 值发生变化。

注意隐写者本身会自动进行哈希随机化处理，哪怕原文件是同一个，每次生成的隐写文件哈希值都不一样，正常隐写文件时**不必考虑**哈希值问题。

[![3e78f26da4d708e61049a599cde829e3.webp](https://file.cangku.moe/images/3e78f26da4d708e61049a599cde829e3.webp)](https://file.cangku.moe/images/3e78f26da4d708e61049a599cde829e3.webp)

- 验证码生成器

使用验证码生成器处理提取码，可以防止被爬虫爬取到链接

[![d72d3b79e10f0e412d7bd101a3058db1.webp](https://file.cangku.moe/images/d72d3b79e10f0e412d7bd101a3058db1.webp)](https://file.cangku.moe/images/d72d3b79e10f0e412d7bd101a3058db1.webp)

示例如下：

[![d55ef7164a6e579b01534ea1dd88eb7f.webp](https://file.cangku.moe/images/d55ef7164a6e579b01534ea1dd88eb7f.webp)](https://file.cangku.moe/images/d55ef7164a6e579b01534ea1dd88eb7f.webp)

- 右键菜单集成

在 v1.2.0 版中，新增了可以**集成软件到右键菜单**的安装脚本和卸载脚本，双击执行即可安装/卸载。功能基于 CLI 模式（默认选择 cover_video 文件下第一个视频）。目前暂时不能处理密码、选择视频等详细操作，如果需要进行这类操作，可以选择右键-打开隐写者GUI

[![d36f4b4f035cdf963cc481991cfa44e8.webp](https://file.cangku.moe/images/d36f4b4f035cdf963cc481991cfa44e8.webp)](https://file.cangku.moe/images/d36f4b4f035cdf963cc481991cfa44e8.webp)

20240801-v1.2.0.1 版本，进一步**集成哈希修改器**功能

[![ef0d856f69b62f7baf724a774cc83bc4.webp](https://file.cangku.moe/images/ef0d856f69b62f7baf724a774cc83bc4.webp)](https://file.cangku.moe/images/ef0d856f69b62f7baf724a774cc83bc4.webp)

以下为详细操作演示

[![fa9b0e5590c07a7c7bc88a016b48eb54.gif](https://file.cangku.moe/images/fa9b0e5590c07a7c7bc88a016b48eb54.gif)](https://file.cangku.moe/images/fa9b0e5590c07a7c7bc88a016b48eb54.gif)

- 密码本

20240828-v1.2.1 版本：解除隐写逻辑新增密码本功能，在 modules/PW.txt 中分行输入密码即可，解除隐写时程序会在密码本中搜索密码并尝试解压（CLI模式和右键菜单一并适配），支持 [解TMD压](https://cangku.moe/archives/216302) 格式的密码本，如下图：

[![eaf2b59d2d9d6fb5205c1095e1df3990.webp](https://file.cangku.moe/images/eaf2b59d2d9d6fb5205c1095e1df3990.webp)](https://file.cangku.moe/images/eaf2b59d2d9d6fb5205c1095e1df3990.webp)

## 5. 经验与技巧分享

### 5.1 资源分享的几个安全级别

(1) **直接上传&分享**：真的勇士，总是敢于直面惨淡的人生和淋漓的鲜血，以及炸链、封号等一系列挫折。

(2) **单层/多层压缩包**：有密码并加密文件名就能防止网盘扫描压缩包中的内容，一定程度上可以抵抗审查，但是无法防止在线解压（手机端可以在线解压包括7z在内的压缩包格式，大于20GB的压缩包目前无法在线解压，但不建议上传这种大文件），如果没有密码，那么参考 (1)

(3)-1 **分卷压缩包**：由于分卷压缩包无法在线解压，安全性较2提高了很多（是否改后缀名，或者有没有混淆文件并无太多影响） 。
(3)-2 **自解压格式压缩包**：格式为exe的压缩包，不需要安装解压软件，直接执行就可以解压。自解压文件也不能在线解压，安全性与分卷压缩包为同一级别。

(4) **其他专有格式的加密文件**：包括但不限于 Cryptomator 、VeraCrypt 等专有格式加密文件。相比于较为通用的压缩包，网盘方不太可能搭载能够解密这些专有格式的功能，所以安全性高于前者。不过无法应对大量举报造成的强制违规。

(5) **隐写文件**：这里指 JPG/PNG/MP4/MKV 等隐写文件，从加密技术层面来看，隐写文件属于3这个级别（隐写文件也不能在线解压，会提示压缩包损坏）。由于其伪装能力强的特性，可以较好混淆审查。不怕举报造成的强制违规，可以申诉（详见 5.3 节）。因此安全性高于上述所有。

(6) **BT、IPFS、自建网盘**：去中心化分享一般来说无法被举报，所以安全性是顶级，自建网盘也是同理。关于举报相关的内容，会在 5.3、5.6 节详细讨论。

总的来说，根据 【**1. 能否加密**】 【**2. 能否在线解压**】 【**3. 能否被举报**】这三个点，可以把分享方式大致划分出 3 个大的安全级别。

关于网盘分享的安全级别排名，感兴趣可以进一步看[**这篇文章**](https://hxcy.top/542211.html)[8]。

### 5.2 隐写文件安全性来源：低可疑度

在选择文件和隐写内容时，需要根据分享资源的大小选择合适的外壳文件，**看上去要合理，不至于让人怀疑**。

比如你的资源大小有 3 个 GB，此时最好就不要选 1、2 分钟的短视频，因为这不太合理，容易让人怀疑；最好选择一个时长 1 到 2 小时的长视频。可以选择低清晰度的电影或者b站上的网课类长视频，这类视频的 360P 大小通常在 300MB 以内。

我也在程序中提供了几个供参考的长视频，大家可以按需选用。**我认为，使用少量的额外流量换取安全性还是比较划算的**。

下面是个人推荐的**资源大小-外壳时长**参考表。

| 资源大小      | 视频时长推荐   |
| --------- | -------- |
| 0-200MB   | 1-3分钟    |
| 200-400MB | 3-15分钟   |
| 400-500MB | 15-30分钟  |
| 500MB-1GB | 30分钟-1小时 |
| 1GB-3GB   | 1小时      |
| 3GB-4GB   | 2小时      |
| 4GB以上     | 2小时以上    |

推荐下载 B 站的视频作为隐写的外壳文件，B 站压制视频较为专业，3 分钟的视频可以保证在 10 MB 以内，**注意不要下到可能会涉及版权问题的视频，比如番剧、UP 充电专享视频等**。不放心的话可以搜索“公有领域”关键词来查找视频，公有领域视频都不会涉及到版权问题。

**隐写外壳下载工具**（B站视频下载工具）
[https://github.com/leiurayer/downkyi](https://github.com/leiurayer/downkyi)

建议的下载参数，画质可以选择 480P 以下，通常不会很糊；但音质建议中质量，否则糊得太明显容易引起怀疑；视频编码选择 H.265 压缩率更高，视频体积更小

![](https://file.cangku.moe/images/f72756532b561bc16ceed41f950ecf96.webp)

对于过大的资源 (>4GB)，可以采用分文件夹或分卷处理的方式，嵌入的外壳视频可以为按顺序分集的动画，这样可疑度会更低一些。目前程序在版本 1.1.2 之后新增了隐写不合理的提醒。

### 5.3 基于隐写的申诉补档技巧

隐写文件的区别于其他网盘分享方式的主要特点为：**不容易炸链，且** **违规可申诉**。

所谓不容易炸链，是指隐写虽然被举报到一定数量（这里用“**少量**”指代 ），会**短暂地进入审核状态，表现为【暂时冻结】或【正在审核】，但是过5-10分钟可自行恢复正常**，**免疫**少量及以下的举报。 

关于此特性的证明，参考[这个试验[5]](https://bafybeiadpfp7wu6qwmyighdel3qw2eqqqacrmyuxfdwc5u4vwmhiw4mqce.ipfs.dweb.link/)

这是以往的任何加密方法都做不到的，如上文所述，网盘对于无法解密又被大量举报的文件会倾向于直接判违规。

不过，隐写文件虽然不容易炸链，但是被**大量**或**海量**举报以后还是有可能炸链的（分别会提示“此文件禁止分享”或者“文件违规根据相关法律法规予以屏蔽”）。

当一个分享炸链以后，我们如果要对其进行补档，通常需要重新压缩以后再上传，之所以不能直接重新分享而要这样做，是因为**违规文件的哈希值已经被网盘记录**，再次上传或者分享网盘都认得这个文件（文件哈希值可以类比人类的指纹），这无疑费时费力，尤其是文件很大的时候，更是一场噩梦。

隐写文件的**可申诉性**给了我们另一种比较方便的解决办法：**我们可以直接对违规文件进行申诉，然后重新分享即可，并不需要一次次地重新压缩上传进行补档**。假如最近一直被人盯着举报，可以选择等待一段时间避过风头之后再申诉让文件“活过来”然后继续分享。

![4e3b022c952cffc89376061f9809c595.webp](https://file.cangku.moe/images/4e3b022c952cffc89376061f9809c595.webp)
此外，面对大量恶意举报时，不建议用大号进行分享，而是建议只用大号上传和申诉，小号来分享，以避免封号可能造成的损失。详情可以参考这篇文章

[[技巧分享] 百度网盘大号传小号分享的操作方法](https://hxcy.top/542051.html)

关于申诉技巧的更多细节，详见 [这篇文章[10]](https://hxcy.top/541697.html#heading-20) 

### 5.4 适度的擦边也是伪装

另一方面，**内容完全没有问题可能也不太好**。

如果被大量举报，有可能会引起人工复查，一个视频明明看着完全没有问题，但却总是被举报色情，这也很可疑。

对此的一个建议是，**假如你的资源可能面临**[**大量举报**](https://bafybeiadpfp7wu6qwmyighdel3qw2eqqqacrmyuxfdwc5u4vwmhiw4mqce.ipfs.dweb.link/)**的风险**，可以使用各类性学相关或者能过审的哲♂学银梦等擦边但不至于被封的视频。

这样在面对大量举报时，可以最大程度降低暴露的风险，假如不幸被封，也可以**合理化申诉理由**。

![6b3f6289b08797becab8518029722d52.webp](https://file.cangku.moe/images/6b3f6289b08797becab8518029722d52.webp)

具体大家可以发挥自己的想象力，这里只是示例，总之：

> **伪装的目的并不是让人挑不出毛病，而是让对方误判，大事化小小事化了**。

### 5.5 个人隐私安全

尽管隐写可以增加文件的安全性，但分享时仍应考虑个人的网络安全和匿名性。例如，在上传期间使用 VPN 或代理；**不要使用包含个人信息的视频**，也**不要总是使用同一个视频作为隐写外壳**等，以降低被追踪和识别的风险。

### 5.6 恶意举报问题


某些被认为有价值的资源有可能会被**资源倒卖者**等恶意团体盯上，所谓资源倒卖者，就是把免费分享的资源拿去贩卖以牟取利益的人，俗称“**倒狗**”。

为了保证利益的**垄断**，倒卖者会举报其他的分享文件使之炸链，从而维持其来源的唯一性（白话：吃独食）。其结果表现就是投稿及其下方传火链接地毯式炸链。（例子：[例子1](https://hxcy.top/493477.html)、[例子2](https://hxcy.top/492146.html)、[例子3](https://hxcy.top/492938.html)

具体来说，倒卖者会使用自动化的脚本对分享文件进行举报。注意**举报的是文件不是链接**，倒卖者会转存想要使之违规的文件，用自己的号分享，然后运行举报脚本持续举报直到文件违规。

这种规模的举报不是隐写文件能够应对的，不仅隐写文件不行，任何正常文件都不行，哪怕是正常文件也会被网盘强制判定违规，也就是说这种违规与文件实际上存不存在违规内容无关，而属于近似于 DDos 的一种**攻击行为**（这也就意味着哪怕秒传也不行），虽然隐写文件可以申诉，但是**如果举报者不能彻底让文件死亡，那就会想要让分享者死亡，与其一个个举报文件，不如直接让分享者封号来的更加省事一些。**

因此假如资源已经被倒卖者盯上（**判断标准是隐写文件分享后很快炸链，并且申诉成功解封以后再次快速炸链**）此时不建议再继续用常见网盘分享，而建议改用 **[IPFS](https://hxcy.top/544580.html)**, **磁链**、**[**自建网盘**](https://cangku.moe/archives/209596)[X5]**、**等不会因举报而和谐的分享方式。

关于更多安全分享以及倒卖者举报的原理分析，参考[**这篇文章**](https://hxcy.top/541697.html)

  

### 5.7 使用视频托管平台来托管隐写文件

  

因为隐写文件既是视频也是压缩包，所以我们可以把隐写文件上传到某些视频平台，把视频平台当成网盘来用。

传统视频网站（例如 B 站）会压缩画质导致隐写内容丢失，但有些基于 [**IPFS**](https://hxcy.top/544580.html) 的网站可以直接下载原文件（比如 [sol.media](https://sol.media/)），这个特点使得它可以用来白嫖存储空间，同时由于此网站实际上把文件托管到 pinata 上（pinata 的稳定性比较好），内容能被 IPFS 网络公开检索到，分享时就不必用网站的视频链接了，而可以用视频的 CID 内容寻址，通过 IPFS 网络下载文件（分享手感很像秒传）。

隐写文件可播放也带来了比较好的安全性，如下图，一眼看上去还算正常：

![o7B9I.jpg](https://pic.cangku.moe/images/2025/01/12/o7B9I.jpg)

网站有 **NSFW** (Not Safe For Work) 分类，上传时可以选择此分类，这样就能够直接上传一些涩涩内容，并且不会显示在左上角的 Trending 中，免得被路人围观。至于界限在哪里，大家可以去看一下这个网站的 NSFW 分区，大致就是一些 AV 级别的内容（童车不建议，二次元童车也不好说，这种情况最好用隐写处理）

由于我们是在白嫖网站的空间，最好秉持隐写文件的一贯原则：【不引起怀疑】，上传时最好看起来像是【正常用户】（~~每天好几十个大 GB 的 Never Gonna Give You Up 上传，不管怎么看都会很奇怪的~~）。大家辛苦一点把自己当成视频搬运工，多去 B 站找几个有价值的视频，就当为这个网站的视频丰富多样性做建设，人人为我，我为人人，顺带薅点羊毛当创作激励，来个双赢乃至三赢！（下载者看视频学到了知识，网站丰富了视频内容和用户活跃度，分享者薅到了羊毛，三赢！）。

除了 sol.media 以外，以下网站也可以用来托管：

[https://odysee.com/](https://odysee.com/) （此网站上传视频等效码率最大16MBps ，因此要注意隐写视频的长度要长一些）

[https://gleev.xyz/](https://gleev.xyz/) （此网站可以直接托管隐写文件）



更多托管平台可以参考这篇文章：

[[技巧分享] 盘点主流IPFS托管平台：功能、限制与推荐指数全面对比](https://cangku.moe/archives/216179) 

 
### 5.8 法律问题


估计能看到这里的朋友都明白，但还是容我多嘴强调一点。

在使用本程序时，请大家遵守必要的相关法律和道德规范。自己的爱好可以分享资源，但是务必不要让这些小圈子里的东西上了台面，也不要去任何官方可以看到的地方跳脸。历史经验无数次告诉我们，小圈子破圈的后果往往是一地鸡毛。（**你！不要让大家都用不了隐写！**）

我们不鼓励使用隐写技术进行非法活动，而是希望通过技术增强个人数据保护和隐私安全。


## 7. 不足与展望

目前的程序仍然存在一些问题，比如合并方法是简单地将 ZIP 文件附加到视频文件的末尾、嵌入 MP4 文件的 moov box 或者 MKV 文件的附件中。这种方法虽然易于实现但也容易被检测到。

后续也许可以考虑使用一种更加隐蔽的方式，例如将 ZIP 文件的内容嵌入到视频文件的某些不太关键的部分，在每个 I 帧后插入一小段数据等。这类做法需要分析视频文件的编码细节，可能需要用到其他库如 FFmpeg 等，具体留待后续研究。

尽管如此，根据文章[[1]](https://cangku.moe/archives/211591)的测试结果，以及[**本测试的结果**](https://cangku.moe/archives/211857)，隐写具有：**① 不易违规 ② 即使违规也**[**可申诉**](https://cangku.moe/archives/212105) **③ 补档方便** 等优势。**在不被特意针对性举报的情况下，这样的隐写方法已经足以认为是一个可以推广的解决方案了**。

今后随着技术的进一步完善，此类隐写方法或许能成为秒传之后安全分享的一个有效手段。

**此程序权当抛砖引玉，欢迎各位积极参与研究**。

隐写文件说明信息一键复制；
```Plaintext
1. 外壳MP4文件为伪装视频，资源被隐写在MP4文件内部。
2. 解压方法：用 WinRAR 改 MP4 后缀名为 ZIP 然后解压。
```

## 8. 总结

本文介绍了资源分享手法到秒传链接为止的历史，证明了举报是引起炸链的主要原因，提出采用隐写技术作为新时代的资源安全分享解决方案，同时分享了一些使用隐写技术时的一些经验和建议，希望能帮助资源分享者更好地活用隐写技术。

随着技术的进步和数字媒体的普及，隐写技术可能会有新的突破，除了之前提到过的插帧法隐写，还可能有深度学习 AI 驱动的隐写系统，这些都可能为资源分享安全问题提供新的解决方案。

> **矛与盾的对抗永不停息，新的时代在呼唤新的解决方案**。

欢迎大家参与到隐写技术的测试和研究中来，共同推动其发展。如果大家对于本程序有什么进一步的改善要求和建议，欢迎在评论区提出，或者在 GitHub 上提 issue。

源代码：[https://github.com/cenglin123/SteganographierGUI](https://github.com/cenglin123/SteganographierGUI)

## 9. 免责声明

<font color="#c0504d"><b>本程序仅用于保护个人信息安全，请勿用于任何违法犯罪活动</b></font>

## 10. 下载链接

[IPFS](https://k51qzi5uqu5dgkmeltawl5a7yfyrmb7gqrxivyqzp9cray1x05xlenbdfatkib.eth.sucks/) 
[蓝奏云](https://wwmh.lanzoul.com/b004hu9ite) 
[Github](https://github.com/cenglin123/SteganographierGUI/releases)


## 附录A：隐写的指令

### A.1 MP4隐写
```sh
copy /b "input.mp4" + "input.zip" "output.mp4"
```
python代码
```python
import subprocess

cmd = [
	'copy', '/b',
	'input.mp4','+',
	'input.zip',
	'output.mp4',
]
subprocess.run(cmd, check=True)
```

### A.2 MKV 隐写（使用 mkvtoolnix）
```sh
mkvmerge -o "output.mkv" "input.mp4" --attach-file "input.7z"
```
python代码
```python
import subprocess

cmd = [
	'mkvmerge', '-o',
	'output.mp4',
	'input.mp4',
	'--attach-file',
	'input.7z',
]
subprocess.run(cmd, check=True)
```

### A.3 其他隐写技术

除了本文中提到的，还有一些其他文件的处理方法也算做隐写：
1. 比如把文件的[二进制数据转译图像像素信息](https://hxcy.top/541610.html)，然后得到一张毫无意义的图片进行存储；
2. 或者当成 8 位的 pcm 数据文件,然后封装转成 wav 文件，得到一个伪装的毫无意义的 wav 文件，还可以再转成 flac 甚至混流进 mkv 里。
3. 又或者，通过直接[修改文件头来快速进行格式伪装](https://github.com/rippod/apate)。

这些方法带来安全性的原理都是类似的，在 5.1 节中有讨论，不过以上方法在易用性上来说不如本文中提到的方法，因为这些方法的解码需要专门的软件，而本文提到的 copy /b 方法常见的解压软件都能解压。在便利性上来说更胜一筹。

## 附录B：MP4隐写技术相关系列文章（时间顺序）

**主要内容**

[1] [[技巧] 用文件隐写来规避网盘和谐](https://cangku.moe/archives/211591)

[2] [**[工具分享] 隐写者：把资源嵌入MP4文件的隐写工具 [资源防炸链解决方案倡议&规避网盘审查技巧探讨]**](https://cangku.moe/archives/211602)

[3] [**[技巧分享] 关于评论区地毯式炸链现象的一些测试及初步猜想 [资源防炸链解决方案倡议]**](https://bafybeiadpfp7wu6qwmyighdel3qw2eqqqacrmyuxfdwc5u4vwmhiw4mqce.ipfs.dweb.link/)

[4] [**[技巧分享] 网盘资源分享的几种安全级别、审核与举报，分享建议 [资源防炸链解决方案倡议]**](https://cangku.moe/archives/212002)

[5] [**[技巧分享] 如何应对恶意举报 - 百度云篇 - 其一 [资源防炸链解决方案倡议]**](https://cangku.moe/archives/212735)

[6] [**[技巧分享] 如何应对恶意举报 - 百度云篇 - 其二 [资源安全分享方案倡议]**](https://cangku.moe/archives/213855)

[7] [**[技巧分享] 百度网盘大号传小号分享的操作方法 [资源安全分享方案]**](https://cangku.moe/archives/214440)



**延伸阅读**

[X0] [1] [**[技巧分享] 防炸教程：如何安全分享资源？**](https://hxcy.top/541697.html)

[X1] [[技术分享] 如何在.mkv格式视频里夹带隐藏文件，附带mkvtoolnix，MkvEdit和gMKVExtractGUI工具](https://cangku.moe/archives/199992)

[X2] [[杂谈] 给新司机的一个简单的科普](https://cangku.moe/archives/186292) (笔者注：此文是关于安全分享的科普)

[X3] [**[技巧分享] IPFS分享资源快速上手及其适用场景浅议 [资源防炸链解决方案]**](https://cangku.moe/archives/212530)

[X4] [[技巧] 利用网盘离线下载分享规避审查](https://cangku.moe/archives/212031)

[X5] [[技巧分享] [自建网盘] 自建网盘cloudreve+离线下载](https://cangku.moe/archives/209596)

[X6] [[高阶文章] 关于新时代文件分享机制的思考](https://cangku.moe/archives/178593) (笔者注：此文介绍了除网盘外的其他分享方案)

[X7] [[技巧分享] 图种的制作与使用](https://cangku.moe/archives/204982)

[X8] [[技巧分享] 防炸教程](https://cangku.moe/archives/179329) (笔者注：本文介绍了网盘常用的分享方案，不过作者有可能要吃电脑屏幕了)

[X9] [[教程] BitTorrent (种子文件) 扫盲 [绅士仓库 tracker 更新] [2020 Rev]](https://cangku.moe/archives/92314) (笔者注：本文是磁力做种的教程)

[X10] [**[技巧分享] [IPFS] 无法被举报的文件分享神器CRUST IPFS操作指南 PART.I**](https://cangku.moe/archives/212812) ( IPFS 托管平台教程)

[X11] [关于百度近日封号的相关措施](https://cangku.moe/archives/178107) (此文也是秒传时代的开端)

[X12] [[南+] 本坛还是有牛马用户啊，低能儿请远离互联网好吗？一口一个敬语问我要资源下载了之后反手就去微软举报，你咋不去网信部举报？说不定给你颁一个好市民奖](https://www.south-plus.net/read.php?tid-1978508.html)

[X2] [[南+] 看看单纯的举报行为会对百度网盘资源有多大的影响](https://www.south-plus.net/read.php?tid-2203531.html)
