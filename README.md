# 常用Altium Designer封装库整理

不定期更新

### 使用方式

```shell
git clone git@github.com:redlightASl/Lib-ADP.git
```

将得到的目录加入AD工程并将其中的`MyPcbLib.PcbLib`和`MySchLib.SchLib`添加到项目中

> **添加到Altium Designer库文件的方式**
>
> 在Components选项卡上方，选择`File-based Libraries Preferences`后，进入`工程`子选项卡，选择`添加库`，并将Lib-ADP中的SchLib和PcbLib文件选中添加
>
> 随后会发现左侧`Projects`选项卡中对应的项目内会出现Libraries子选项，即被添加到本工程的Lib-ADP

如果新建了一个git项目，可以使用以下指令添加本子模块（submodule）到git项目内

```shell
git submodule add git@github.com:redlightASl/Lib-ADP.git <子模块目录>
```

使用

```shell
git submodule update --remote --force
```

强制更新本地ADP到最新版本

### 版本更新记录

当前版本：`beta0.3`

* 2022.11.3前-beta0.1
* 2022.11.3-beta0.2
* 2023.7.13-beta0.3
