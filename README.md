# 315MHz ASK Transmission Circuit

We use the TH72002 chip in our circuit, whose datasheet can be found in attachment.

We tried to apply the test circuit in datasheet provided by Melexis. See below:
<img src="./img/1.JPG"> 

The parameters of design:
<img src="./img/2.JPG"> 

### 设计简介

Multisim 14中没有TH72002芯片，本文采用的是自己添加封装。同样的，晶振R315也没有出现在元件库中，也是自己添加封装。注意好管教对应关系就可以。采用的R315参数如下：
<img src="./img/3.JPG"> 

### 附件

附件包含Multisim电路图以及ultiboard制板用图。命名为“PCBUse”的文件只是为了制板使用，只为了看封装信息，所以相同封装的表面表贴的器件均用电容替代。最终的设计图仍然有2处错误，不过印制的时候可以用碳素笔画上。

### 最终成果

多次尝试印制板子失败后，直接在整块铜板上用刻刀刻开元件管脚所在的区域制板成功。可以发射出315MHz的OOK调制信号。