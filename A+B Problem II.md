# A+B Problem II

## 背景

新一年的OO课程开始了，HansBug准备给大家寒假增添一点乐趣。

## 题目描述

这是一个很简单的问题，即求两个十进制整数的和。**然而这一次，事情有那么一点不同**。

## 输入格式

第一行包含两个十进制整数，用空格分隔，分别表示<img src="https://latex.codecogs.com/gif.latex?a" title="a" />和<img src="https://latex.codecogs.com/gif.latex?b" title="b" />。

对于

## 输出格式

一行，包含一个十进制整数，即为<img src="https://latex.codecogs.com/gif.latex?a+b" title="a+b" />。

如果输入的数据不合法，则需要输出`WRONG FORMAT!`

## 样例

|  #   | 输入                      | 输出          | 解释                               |
| :--: | ------------------------- | ------------- | ---------------------------------- |
|  1   | 1 2                       | 3             | 显然。                             |
|  2   | 10000 20000               | 30000         | 更加显然。                         |
|  3   | -10000000000 -20000000000 | -30000000000  | 非常显然。                         |
|  4   | -+10000 300000            | WRONG FORMAT! | -+10000整数格式错误。              |
|  5   | -10000 3000 123           | WRONG FORMAT! | 包含的整数个数不是两个，格式错误。 |

## 说明

### 约束信息

* 不保证所有输入的数合法
  * 对于一个整数的合法性，判定标准定义为：对于一个整数，应该由一个或多个连续的`0`~`9`数字构成（允许任意数量的前导零），且数字开头可以包含一个正号（`+`）或者（`-`）。
  * 对于输入数据的行内，应当包含且仅包含两个合法的整数。
  * 如果输入数据违反了上述两条，则需要输出`WRONG FORMAT!`
* 保证所有输入的合法整数满足<img src="https://latex.codecogs.com/gif.latex?\left(&space;-10^{100000}&plus;1&space;\right)&space;\leq&space;a,&space;b&space;\leq&space;\left(&space;10^{100000}-1\right)" title="\left( -10^{100000}+1 \right) \leq a, b \leq \left( 10^{100000}-1\right)" />
* 不保证<img src="https://latex.codecogs.com/gif.latex?a" title="a" />、<img src="https://latex.codecogs.com/gif.latex?b" title="b" />之间仅包含一个空格
* 输出中请不要包含多余的正负号

### 需要先学习的技能

* 基本的Java语法
* Java的基本io操作（推荐使用`Scanner`）
* Java的基本整数数据类型
* （二选一）Java的数组基本操作 / Java的高精度数据类型（具体可以百度）
* 正则表达式的基本使用





