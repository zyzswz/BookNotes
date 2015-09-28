这一节主要学习计算机数据的处理与表示，涉及的知识点有：
- 补码
- 反码
- 移码
- 二进制的运算
- 表示法


计算机可以处理各种信息，如数字，文本，音频，图像和图形，视频等。这里注意：

- 数据：基本值或事实
- 信息：用有效的方式组织或处理过的数据

这些数据最终被存储为**二进制数字**

# 一. 二进制的运算
二进制除了与十进制一样可以进行**四则算术运算**之外，还可以进行**逻辑运算**, 因为它只有两个数码，代表两种截然相反的状态.

## 1.1 加减运算
二进制的四则算术运算与十进制一样

### 1.1.1 加法运算法则

0+0=0， 0+1=1， 1+1 = 10（相当于十进制的2）

也就是**逢2进1，进1当1，借1当2. 与十进制的逢10进1道理一样**

![](https://raw.githubusercontent.com/BeginMan/BookNotes/master/CS/media/cs11.png)

### 1.1.2 减法运算法则

1-1=0, 1-0=1, 0-0=0,0-1=-1

**如果被减的二进制位为0，而减数的二进制位1， 则需要向高位借1，借一当二，与十进制的借一当10 一样**



# 二. 表示法
分为：

- 二进制表示法
- 数字数据表示法，如负数表示法、实数表示法
- 文本表示法：重点在字符的表示
- 音频信息表示法
- 图像和图形表示法
- 视频表示法

Over.

