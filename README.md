# 七平拼音

## 喜欢请给个star或者fork，感谢啦~

原始配置和词库由[白霜拼音](https://github.com/gaboolic/rime-frost)与[日语词库](https://github.com/gkovacs/rime-japanese)修改而来。

白霜拼音的词库比起雾凇拼音和原版来说已经非常全面了，适合作为一款rime的起点，不过想要更加个性化与达到开箱即用，我就对白霜拼音进行了一定的修改。

**本词库偏向更多面向小说作者与网络冲浪二次元等对输入个性化要求较高的用户**~~(目标变成小男娘专用词库)~~

主要是添加腾讯词库、萌娘百科词库与自己制作的新词库，这一步进行了加法。

同时对原白霜拼音各类文件与备选词进行了一定的精简，删除了对使用者意义不大的注释，便于维护。

本词库支持全拼与双拼，持续更新中。

### 近期目标

制作中文互联网网络热梗词库

制作起点，创世，刺猬猫，菠萝包，飞卢等多小说平台常用词补充词库

完整校对，精简白霜词库原有词库

### 使用方法

使用方法基本同白霜拼音，下文为白霜拼音的内容。

- 符号 /fh 更多符号详见`https://github.com/gaboolic/rime-frost/blob/master/symbols_v.yaml`
- 带调韵母 /a /e /u 等
- 日期与时间 rq sj xq dt ts
- 开启辅助码 ` [墨奇辅助码拆分说明](https://moqiyinxing.chunqiujinjing.com/index/mo-qi-yin-xing-shuo-ming/fu-zhu-ma-shuo-ming/mo-qi-ma-chai-fen-shuo-ming)
- 部件拆字反查 uU
- unicode字符 U
- 数字金额大写 R
- 农历 N
- 计算器 V

### 如何安装&配置文件路径

#### 手动下载安装

下载本仓库的压缩包 Code - Download ZIP（或者下载[releases](https://github.com/C1ement314/rime-clement/releases)最新的 source-code.zip），解压到如下路径即可

- Windows: `%APPDATA%\Rime` （可以在右下角小狼毫输入法右键打开菜单选用户文件夹）复制完之后，去输入法设定里选择白霜拼音，然后重新部署
- Mac
  - [鼠须管](https://github.com/rime/squirrel)路径为 `~/Library/Rime`
  - [fcitx5-Mac 版](https://github.com/fcitx-contrib/fcitx5-macos)路径为 `~/.local/share/fcitx5/rime`
- Linux
  - [fcitx5-rime](https://github.com/fcitx/fcitx5-rime)路径为 `~/.local/share/fcitx5/rime`
  - fcitx5 flatpak 版的路径 `~/.var/app/org.fcitx.Fcitx5/data/fcitx5/rime`
  - [ibus-rime](https://github.com/rime/ibus-rime)路径为 `~/.config/ibus/rime`
- Android
  - [fcitx5-安卓版](https://github.com/fcitx5-android/fcitx5-android)路径为 `/Android/data/org.fcitx.fcitx5.android/files/data/rime`
  - [同文](https://github.com/osfans/trime)路径为 `/rime`
  - [雨燕](https://github.com/gurecn/YuyanIme) 已内置白霜词库词频，直接安装使用即可
- iOS [仓输入法](https://github.com/imfuxiao/Hamster) 目前已内置，也可以通过【输入方案设置 - 右上角加号 - 方案下载 - 覆盖并部署】来更新白霜拼音。

#### 通过 Git 安装

**首次安装：**

根据用户使用的系统、安装的软件不同，先cd到对应的配置文件的父级目录(例如Windows为`%APPDATA%`、mac鼠须管为`~/Library/`)，然后执行以下命令：

`git clone --depth 1 https://github.com/C1ement314/rime-clement Rime`

**后续更新：**

在 Rime 文件夹执行 `git pull` 即可。

- Mac: `cd ~/Library/Rime && git pull`
- Windows: `cd "$env:APPDATA\Rime" && git pull`
- 其他系统以此类推

#### 通过 东风破 安装（暂未支持）

抱歉我还没搞懂怎么使用和上传东风破

### 无智能模型时的输入效果

![alt text](others/img/gegegojx.png)

![alt text](others/img/mggjdgg.png)

![alt text](others/img/ddmdd.png)

![alt text](others/img/tushuguancangshu.png)

![alt text](others/img/znjldkd.png)

![alt text](others/img/kudsvqw.png)

![alt text](others/img/cqlbtdmdfu.png)

![alt text](others/img/djbwv.png)

![alt text](others/img/刚交的朋友.png)

![alt text](others/img/刚交的好朋友.png)

![alt text](others/img/刚交的好朋友2.png)

![alt text](others/img/衍射.png)

### 鸣谢

白霜词库 <https://github.com/gaboolic/rime-frost> 七平词库的初始词库、绝大部分配置来自白霜词库。

日语词库 <https://github.com/gkovacs/rime-japanese> 优良日语词库，足够用户进行基础的日语输入。

萌娘百科词库 <https://github.com/outloudvi/mw2fcitx> 萌娘百科词库，拥有大部分二次元词条。

Rime <https://github.com/rime> 没有Rime，就没有现在的词库制作。
