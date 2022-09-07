# 常用Altium Designer封装库整理

不定期更新

使用方式

```shell
git clone git@github.com:redlightASl/Lib-ADP.git
```

将得到的目录加入AD工程并将其中的`MyPcbLib.PcbLib`和`MySchLib.SchLib`添加到项目中

如果新建了一个git项目，可以使用以下指令添加本子模块（submodule）到git项目内

```shell
git submodule add git@github.com:redlightASl/Lib-ADP.git <子模块目录>
```

使用

```shell
git submodule update --remote --force
```

强制更新本地ADP到最新版本
