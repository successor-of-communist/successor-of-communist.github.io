---
title: C++11 new features
date: 2021-03-27 22:17:34
tags:
- C++11
categories:
- C++
---

## 右值引用
左值：可以存取地址并且有名字的（也就是可以放在=左边的）
右值：不能取地址没有名字的（不能放在=右边的）
纯右值：运算表达式产生的临时变量、不和对象关联的原始字面量、非引用返回的临时变量、lambda表达式等都是纯右值
将亡值：也就是即将销毁的值
纯右值和将亡值都是右值
左值引用就是普通的引用&，右值引用是&&
```
type &name=exp;
type &&name=exp;
```

左值引用必须要能取地址
右值引用我理解就是将地址指向临时变量的地址，std::move就是将原来的生成一个临时变量

## 初始化列表
可以直接在变量名后面加上初始化列表来进行对象的初始化

## lambda    
##nullptr
## final override default delete explicit 
## constexpr  
## long long int

## 智能指针

## 委托构造函数

## 正则表达式

## 哈希表


看这里
[https://xie.infoq.cn/article/0c68359d19103ca2009006070](https://xie.infoq.cn/article/0c68359d19103ca2009006070)
[https://harttle.land/2015/10/08/cpp11.html](https://harttle.land/2015/10/08/cpp11.html)
