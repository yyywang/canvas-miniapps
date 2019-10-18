# canvas 实现的小 demo

## 1. 简易弹幕

### 1. 简介

全屏弹幕，可调节弹幕的**字体样式、字号、颜色、宽度、速度**。

### 2. 实现思路

1. 定义一个对象保存单条弹幕的数据
2. 定义一个数组保存所有弹幕对象
3. 隔一个时间段修改所有弹幕中的位置参数
4. 重新绘制所有弹幕