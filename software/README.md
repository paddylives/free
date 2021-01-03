# 装新电脑流程 
## 1. 修改密码

控制面板=>用户账户=>更改账户类型=>双击想要更改的账户=>更改密码

## 2. 固定IP
## 3. 关闭新安装软件时弹出的是否允许提示
## 4. [修改桌面存储地址](https://jingyan.baidu.com/article/c74d60009d1f2f0f6b595d64.html)
## 5.修改电脑时区
控制面板=>日期与时间=>更改时区=>曼谷、河内
## 6.关闭系统更新
2. window+r 输入services.msc 打开，找到Windows Update，右键选择停止，双击进去启动类型选择禁用，点击应用然后关闭

控制面板-安全和维护”中找到左侧“更改用户账户控制设置”项目，进去之后根据自身的实际需求调整滑块位置即可。可以在安装驱动程序和常用软件时选择“从不通知”，而在正常使用电脑时，调整到中等或最高级别的“始终通知”，确保安全
## 7.添加开机自启动
- 1. 自启动软件创建快捷方式
- 2. window+r 输入shell:startup 打开启动文件夹，把快捷方式放入即可生效，禁用在任务管理器->启动里禁用

## 7.禁用 one Drive

1. windows+R 运行命令 gpedit.msc 打开本地组策略编辑器窗口
2. 依次点开 计算机配置=>管理模板=>Windows组件=>OneDrive
3. 找到“禁止使用OneDrive进行文件存储”一项，并双击打开其编辑窗口
4. 在打开的编辑窗口中选择“已启用”一项，点击确定按钮完成禁用


## 8.关闭电脑通知

设置=>系统=>通知和操作 关闭 有关Windows提示通知

## 9.右键添加cmd [下载cmd可执行文件](./OpenCmdHere.reg)

## 10.安装软件
- KMS Tools Portable v20201101.7z [下载](./MSVBCRT.AIO.2020.12.09.7z)
kms激活工具
- MSVBCRT.AIO.2020.12.09 [下载](./MSVBCRT.AIO.2020.12.09.exe) [来源](https://www.ghpym.com/yxkhj.html)
微软常用运行库合集
- Chrome浏览器 [官网](https://www.google.cn/chrome/)
设置：搜索引擎、语言<高级-语言-新增中文简体右面三个小点选择语言>等

- VSCode [下载(1.51.1)](./VSCodeSetup-x64-1.51.1.exe) [官网](https://code.visualstudio.com/)
插件：Chinese、Auto Close Tag、Auto Rename Tag、Bracket Pair Colorizer、Live Server、Markdown Preview Enhanced、open in browser、Path Intellisense、Vetur等

- Xshell7 [下载](./Xshell-7.0.0049p.exe) [官网](https://www.netsarang.com/zh/free-for-home-school/)

- Xftp7 [下载](Xftp-7.0.0049p.exe) [官网](https://www.netsarang.com/zh/free-for-home-school/)

- 迅雷11 [下载](./XunLeiWebSetup11.1.3.1122dl.exe) [官网](https://www.xunlei.com/)

- 7z解压 [下载](./7z1900-x64.exe) [官网](https://sparanoid.com/lab/7z/)

- vlc播放软件 [下载](./vlc-3.0.5-streamer_4160666189.exe) [官网](https://www.videolan.org/)

- raidrive挂载网盘 [下载](./raidrive-2020-11-30.exe) [官网](https://www.raidrive.com/)

- git版本控制工具 [下载](./Git-2.29.2.2-64-bit.exe) [官网](https://git-scm.com/)

- TortoiseGit[下载](./TortoiseGit-2.11.0.0-64bit.msi) + TortoiseGit-LanguagePack-zh-cn[下载](./TortoiseGit-LanguagePack-2.11.0.0-64bit-zh_CN.msi) [官网](https://tortoisegit.org/download/)
puttygen.exe 生成公私钥，公钥放在 gitlab 设置=>公钥里，使用pageant.exe 加载私钥。为使每次启动Putty后私钥文件自动加载，右键"开始菜单》PuTTy》Pageant"，选择“更多》打开文件位置”，再右键Pageant，选择属性，在 "目标(T)"一栏里空一格后添加 "C:\Program Files (x86)\PuTTY\private-rsa-key.ppk" -c "C:\Program Files (x86)\PuTTY\putty.exe"
其中，"C:\Program Files (x86)\PuTTY\private-rsa-key.ppk"是刚刚生成的私钥文件地址，"C:\Program Files (x86)\PuTTY\putty.exe"是putty可执行文件地址。

- node [下载(14.15.1)](./node-v14.15.1-x64.msi)  [官网](https://nodejs.org/zh-cn/)
修改为阿里源
```
npm config set registry https://registry.npm.taobao.org -g
npm config set disturl https://npm.taobao.org/dist --global
npm config set sass_binary_site https://npm.taobao.org/mirrors/node-sass/ -g
npm config set phantomjs_cdnurl https://npm.taobao.org/mirrors/phantomjs -g
npm config set electron_mirror https://npm.taobao.org/mirrors/electron/ -g
```

- Postman [官网](https://www.postman.com/)

- Snipaste截图工具 [下载](./Snipaste-2.5.5-Beta-x64.zip) [官网](https://zh.snipaste.com/)

- 星愿浏览器 [下载](./Twinkstar_v7.2.1000.2011_ReleaseA.exe) [官网](https://www.twinkstar.com/)
下载视频

- 搜狗输入法 [下载](./sogou_pinyin_98a.exe) [官网](https://pinyin.sogou.com/)

- Navicat15安装包和破解 [下载](./Navicat15安装包和破解工具.zip) [官网](http://www.navicat.com.cn/products#navicat/)

- Everything搜索 [下载](./Everything-1.4.1.988.x86-Setup.exe) [官网](https://www.voidtools.com/zh-cn/)