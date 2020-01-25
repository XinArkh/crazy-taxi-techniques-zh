# crazy-taxi-techniques-zh

本手册是对[该网站](http://www.crazytaxi.net/)的**非官方**中文翻译，并稍做补充。

《疯狂出租车》([Crazy Taxi](https://en.wikipedia.org/wiki/Crazy_Taxi)) 是我小时候最早接触的电脑游戏之一，留下了很多美好的回忆，现在怀着怀旧的心情做这么一件闲事，希望这款老游戏能够继续继续发挥余热，给更多人带来欢乐。

<img src="./crazy-taxi.png" height=260 style="margin: 0 auto;" />

**NOTE**: 后面章节的翻译尚未全部完成，欢迎 pull request 贡献力量。

## 本地构建

教程已托管至Read the Docs，可以随时[在线阅读](https://crazy-taxi-techniques-zh.readthedocs.io)。如果需要在本地构建离线文档，可按照以下方式操作：

1. 将该仓库 clone 至本地，然后进入项目根目录。
2. 按照`requirements.txt`中所列举的环境要求自行安装所需要的 Python 依赖库。
3. 通过`make`命令构建文档。

**Linux 下的 make 命令：**

```shell
make html
```

**Windows 下的 make 命令：**

```shell
./make.bat html
```

构建好的 html 文档位于`root/build/html`。

