# Portune

Portune是一个适用于[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot) v2的PCR角色每日运势插件，在nonebot插件vortune原代码基础上改动以适配Hoshino

## 安装方法：

- 将`portune`文件夹复制到`hoshino\modules`文件夹下；

- 打开`portune`文件夹下的`portune.py`，按照注释选择编辑：
    1.帮助文本
    2.每日抽签次数

- 将`portunedata`文件夹复制到hoshino的资源文件夹`res\img`文件夹下；

- 最后记得在`hoshino\config\__bot__.py`的`MODULES_ON`中加上`portune`


## 致谢
portune是从xcwbot上的vortune模块修改而来的，感谢原代码作者**fz6m**
项目地址：https://github.com/fz6m/nonebot-plugin

感谢**zzbslayer**对代码的重构
项目地址：https://github.com/zzbslayer/KokkoroBot-Multi-Platform

## Change Log

#### 2020.09.13
- 增加一波新角色

- 改变读取方式，简化代码(zzbslayer)

- 转用base64发图，本地不再存储
