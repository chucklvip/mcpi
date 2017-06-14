mcpi库 (Python2.7版本)
====================================


## Minecraft Pi Socket API 对应的Python的库文件


## 使用方法


### 安装

```

python setup.py install

```

### 使用(以传送功能为例)

```

import mcpi.minecraft as minecraft

#NOTE - replace "player" below with your name

mc = minecraft.Minecraft.create(address="192.168.1.200", name="player") 

mc.player.setPos(0, 100, 0)

```


### 原始插件和API地址：
[https://github.com/zhuowei/RaspberryJuice.git](https://github.com/zhuowei/RaspberryJuice.git)


