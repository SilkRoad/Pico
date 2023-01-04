# PicoZeroTetris俄罗斯方块游戏
## 所需硬件
- PicoZero微控制器（微雪出品）
- 1.54寸LCD彩色显示器
- 面包板
- 按键
- 蜂鸣器
- 杜邦线

## 使用方法
- 按住PicoZero控制器上的ROOT按键不放开，并将其插入到电脑USB口
- 此时电脑会将PicoZero识别为存储器
- 松开ROOT按键
- [下载](https://micropython.org/download/rp2-pico/rp2-pico-latest.uf2)并上传固件至PicoZero
- 将PicoGameBoy.py、st7789.py、tetris_title.bin和tetris.py四个文件复制到PicoZero的根目录
- 按照下面的电路图连接元器件

![DIAGRAM](https://github.com/SilkRoad/Pico/blob/main/PicoZeroTetris/images/CircuitDiagram.png?raw=true)
