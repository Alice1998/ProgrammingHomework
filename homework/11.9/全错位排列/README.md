# 全错位排列

## 题目描述

我们定义一个全错位排列，为1~n的一个全排列{a1, a2, a3, … , an}，并且满足对于i=1,2,…,n，有ai≠i

现在给定n，求长度为n的错位排序个数

由于结果可能很大，答案只需要mod 109+7输出即可

## 输入描述

一行一个正整数n，含义由题中所述

## 输出描述

一行一个整数，长度为n的错位排序数mod 109+7的值

## 样例输入

	5

## 样例输出

	44

## 注释

N≤105

运算的中间过程可能会超出int范围，建议使用long long进行运算