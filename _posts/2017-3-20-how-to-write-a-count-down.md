---
layout: post
title:  "介绍二进制、八进制、十进制、十六进制及其转换"
categories: 数据进制
tags:  JavaScript
author: Tie-Dan
---

* content
{:toc}

本文将详细介绍二进制、八进制、十进制、十六进制及其转换

## 进制的写法

```js
/**
 * 二进制:由0,1组成。 以0b开头
 * 八进制:由0,1..7组成。以0开头
 * 十进制:由0,1..9组成。整数默认是十进制
 * 十六进制:由0,1..9,ab..f(大小写均可)组成。以0x开头
 */
```
进制:是一种进位的方式。x进制,表示逢x进1






## 数据存储的原理

计算机的电子元件的状态是开和关。那么我们表达数据的时候 也是按照开，关的状态来表示  
 如果我们只有两种状态表达的数据是比较少的，而我们常见的数据：字母、数字、标点符号等比较多两个状态肯定是不够的
 为了能够表示更多的数据 国际组织就规定：用8个这样的信号表示一个数据，这个数据的单位叫：字节。后来我们就通过数字1,0分别表示开和关 请看下图：
<img src="https://github.com/Tie-Dan/jekyll_demo/blob/master/common_Img/jinzhi_1.png?raw=true" alt="哥们！你网速太慢了">

## 其它转十进制
公式：每一位的系数*基数^权次幂相加
<img src="https://github.com/Tie-Dan/jekyll_demo/blob/master/common_Img/jinzhi_2.png?raw=true" alt="哥们！你网速太慢了">
## 十进制转其它
只需记住一句话:除基取余 直到商为0 余数反转
<img src="https://github.com/Tie-Dan/jekyll_demo/blob/master/common_Img/jinzhi_3.png?raw=true" alt="哥们！你网速太慢了">
## 任意进制之间转换
任意之间转换有2中方法:  

1. 通过十进制转一下
2. 拆分法

<img src="https://github.com/Tie-Dan/jekyll_demo/blob/master/common_Img/jinzhi4.png?raw=true" alt="哥们！你网速太慢了">