# 数学黑洞

## 题目描述

任意一个4位自然数，将组成该数的各位数字重新排列，形成一个最大数和一个最小数，之后两数相减，其差仍然为一个自然数。重复上述运算，会发现一个神秘的数。请编程计算这个神秘的数和通过几次运算能得到这个数。


## 输入描述
一个4位正整数


## 输出描述
这个神秘的数和运算的次数，用空格隔开


## 样例输入
	4321

## 样例输出
	6174 3

## 注释
大数：取这4个数字能构成的最大数，本例为：4321；

小数：取这4个数字能构成的最小数，本例为：1234；

差：求出大数与小数之差，本例为：4321-1234=3087；

重复：对新数3087按以上算法求得新数为：8730-0378=8352；

重复：对新数8352按以上算法求得新数为：8532-2358=6174；

重复：对新数6174按以上算法求得新数为：7641-1467=6174

在第三次计算中已得到6174，则输出计算了3次