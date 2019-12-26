---
title: 关于C++的学习手册
permalink: about-cpp-study-manual
date: 2019-01-18 19:40:35
categories:
- C++
tags:
- C++
---

# 按照惯例 写在前面

![](https://raw.githubusercontent.com/liutiantian233/Blog/master/201901/about-cpp-study-manual-1.jpg)

这是一个用于CS专业的学生或有志于进行更深入地了解编程的人。开始通过引入C++语言和标准模板库STL，使用由C++11的标准添加最新的元件，并且移动到更先进的数据结构和算法工作。

<!-- more -->

准确的说，这其实只能算是一个关于我学习C++过程中的检索与目录，我可不认为几篇简简单单的博客，就可以统筹概括完C++详细的知识点，越是经过深度的学习，越是发觉C++的强大，不可与同日的Python相比。

我记得在知乎上有人把C++和物理作类比，我很同意。理论物理是一场无尽的旅程，总有最前沿的东西。

> 我从小就对物理感兴趣，于是我开始钻研物理，到现在，我早已是物理学博士，可我仍然不知道物理到底是什么。

所以我的求知欲只能暂且到此为止，C++亦是如此！

到起草这篇博客开始，现在已经开学三周了。C++简单的皮毛也了解了一下，主要的程序和实验问题，我将会逐步更新至我的GitHub之上。

# 目录与检索

看目录之前先讲个笑话：

> C语言说：我们提供标准外壳，零件和电子元件，您可以一个零件一个零件，亲手组装出任何机器。
>
> Python说：我就像DIY爱好者的3D打印机一样，作为编程语言中真正的多面手，我们致力于让用户轻松地完成他们的工作。另外，我们也有巨量的套壳件，能让你用我们的方式使用友商的产品。不过，为了加工的方便，我们的作品一向是以塑料为主要材质的。所以请不要让它干太重的活，否则可能受不了如此沉重的折磨！
>
> Go等其他语言：我们提供专门为某一类产品定制的集成模块，比如发动机，变速箱等等，您可以利用这些模块定制化特定种类的产品。
>
> Java语言：我们是软件行业的蒸汽朋克，是工业时代的杰出代表。我们的产品一向以大负载，强功率著称，是你处理大量需求的不二选择。不过，请不要频繁地开关这些大家伙，因为那样的话你将浪费90%的燃料在预热机器上。
>
> C++语言：我们提供这个世界上所有产品的集成模块，您可以快速地制作任何东西。相应地，我们还有一本长达1000页的产品说明，请务必仔细阅读，以免您不幸将飞机螺旋桨怼到潜水艇上。

至于为什么要讲这个笑话，因为我想说：**C++语言的野心非常大，但，你的野心不必这么大！**

并且随着大野心C++的逐步更新，一切教程语言都是会被改变，所以我推荐的第一个目录就在这里，[中文的C++官方手册](https://zh.cppreference.com/w/首页)，一切以官方为准。

1. 第零周：关于C++的入门
   1. [对于环境的搭建与编译器的选择](https://liutiantian233.github.io/tech/2019/mac-cpp-environment.html)
   2. [一个简单的C++程序](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%201%20周的笔记.md)
   3. [UNIX的基础命令](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/UNIX基础命令.md)
2. 第一周：变量类型与表达式的算数运算
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%201%20周的笔记.md)
   2. 第一周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab01)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj01)
3. 第二周：控制语句
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%202%20周的笔记.md)
   2. 第二周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab02)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj02)
4. 第三周：函数和更多的程序类型
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%203%20周的笔记.md)
   2. 第三周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab03)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj03)
5. 第四周：字符和字符串的标准模版库
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%204%20周的笔记.md)
   2. 第四周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab04)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj04)
6. 第五周：函数和更多的程序类型
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%205%20周的笔记.md)
   2. 第五周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab05)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj05)
7. 第六周：头文件和Vector
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%206%20周的笔记.md)
   2. 第六周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab06)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj05)
8. 第七周：异常处理和迭代器
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%207%20周的笔记.md)
   2. 第七周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab07)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj06)
9. 第八周：通用算法和匿名函数
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%208%20周的笔记.pdf)
   2. 第八周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab08)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj07)
10. 第九周：关联容器
  1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%209%20周的笔记.pdf)
  2. 第九周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab08)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj07)
11. 第十周：C++的面向对象编程和类的初级概念
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%2010%20周的笔记.pdf)
   2. 第十周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab09)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj08)
12. 第十一周：再探C++的类与对象
   1. [论述部分](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%2011%20周的笔记.pdf)
   2. 第十一周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab10)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj09)
13. 第十二周：数组和动态存储
   1. [论述部分 - 数组](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%2012%20周的笔记.pdf) 和 [论述部分 - 动态存储](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%2012%20周的笔记%20-%20动态存储.pdf)
   2. 第十二周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab11)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj09)
14. 第十三周：类的模版和动态存储
   1. [论述部分 - 类的模版](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%2013%20周的笔记.pdf) 和 [论述部分 - 动态存储](https://github.com/liutiantian233/Blog/blob/master/基于Primer的笔记/基于Primer第%2012%20周的笔记%20-%20动态存储.pdf)
   2. 第十三周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab12)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj10)
15. 第十四周：链表详解 Linked List 和 BigO 算法
   1. 第十四周的[实验程序](https://github.com/liutiantian233/CPP-Lab/tree/master/Lab13)和[项目](https://github.com/liutiantian233/CPP-Project/tree/master/Proj11)
16. 总结：[错题簿 Wrong Book](https://github.com/liutiantian233/CPP-Project/tree/master/Wrong%20book)

粗略地说，我的这篇开发手册将被划分为两个部分：

- 学习C++和STL，并将它应用到一些实际例子。
- 建立我们自己的数据结构和算法（内存管理，模板等等）

我介绍一些课题是：选择和迭代，字符串，函数，其他的数据结构（载体，字符串，地图等）文件的I/O和通用的算法，最后是用户自定义的Class。

# 关于编码的规则

在这个过程中，我们将遵守一套约定关于我们如何在程序命名变量，函数和常量，我们如何缩进等。虽然编码规则往往是任意的，选择一个一致的组织。我们将选择使用[谷歌编码标准](https://google.github.io/styleguide/cppguide.html)，可以在那里寻找，并找到正确的标准答案。

# 参考链接

[来自官方手册](https://zh.cppreference.com/w/首页)

C++ Primer中文译本（由于文件过大，需自行下载或[联系我](https://liutiantian233.github.io/about/)）