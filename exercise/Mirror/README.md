# Mirror
## 题目描述

Mr.Chu的桌子上放着一面梳妆镜，作为他的室友，ufozgg总是能见到镜子里透出的点点春光。为了免受大功率日西带来的伤害，他只好躲进自己的幕帘里避风。由于日西过猛照得ufozgg意识模糊，他感到有点晕，眼前满是镜子里的倒影。ufozgg努力回想着刚刚看到的画面，不过由于大脑处于短路状态，他看到的图像可能经过了若干次镜面翻转拼接后而来。在经过镜面翻转拼接后，一张x \* y的图像b会变成一个2x \* y的图像c，其中c的上半部分就是b，下半部分和b对称。

zgg努力想看清镜子里的人到底长啥样，于是他想知道，能够通过若干次（可以是零次）镜面翻转拼接成他看到景象的图像最少由多少行构成？

## 输入描述

第一行两个整数N，M表示ufozgg看到的图像是N \* M的。

接下来N行每行M个整数（0或者1）描述ufozgg看到的图像。

## 输出描述

一行一个整数表示答案。

## 样例输入

	4 3
	0 0 1
	1 1 0
	1 1 0
	0 0 1

## 样例输出

	2

## 注释

1<=N, M<=100