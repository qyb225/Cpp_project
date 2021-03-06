﻿# 多项式计算器
---
### 功能概要
这是一款基于C++的程序，用进行多项式的一般计算。
它具有以下功能：

* 多项式的化简
* 多项式加减
* 多项式相乘
* 多项式求导
* 判断两个多项式是否相等
* 多项式代入特定点求值

---
### 使用操作说明

#### 如何运行该程序：

首先，请将五个源代码文件放在相同的文件夹中。在Windows环境中，用 g++/VC 编译main.cpp文件并运行生成的文件即可。

接下来运行程序并进入主页面，选择相应的功能，按照提示依次输入多项式，每次输入完成后按回车键即可。

#### 输入：

注意输入必须合法，如果你想要输入多项式**3x ^ 2  - 1**，需要输入**(3,2)(-1,0)**。也就是用一个括号表示一个多项式中的一项，逗号的左边代表多项式的系数，右边代表多项式的指数。输入过程如此以外没有任何限制，多项式不必简化也不必降幂。

#### 输出：

输出保证用户友好性，程序会按照我们平常的书写习惯输出结果。结果降幂输出。

#### 小技巧：

任何时候如果用户希望返回到初始菜单的时候，只需要输入大写的字母'B'，再按回车即可返回到初始菜单。
