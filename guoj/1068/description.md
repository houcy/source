
# 题目描述

「清明时节雨纷纷，路上行人欲断魂。」

2075 年的清明没有春雨。在漫天飞雪的笼罩下，穿行在冰原间的，只有载着人类微薄希望的雪地车。

遥遥 4.22 光年的征途，对于地球这孤独的旅人而言，恐怕也是无比寂寞的吧。

距离苏拉威西只有一百公里了，车内的空气比窗外更加冰冷。四双眼睛紧盯着艾莉芬面前的屏幕，那是控制行星发动机的关键程序：春节十二响。他需要将其部署到电力控制系统的一个芯片中。

「春节十二响」由 $n$ 个子程序构成，第 $i$ 个子程序所需的内存空间是 $M_i$。这 $n$ 个子程序之间的调用关系构成了一棵以第 $1$ 个子程序为根的树，其中第 $i$ 个子程序在调用树上的父亲是第 $f_i$ 个子程序。

由于内存紧张，电力控制芯片上提供了一种内存分段机制。你可以将内存分为若干个段 $S_1, S_2, \dots, S_k$，并将每个程序预先分配到一个固定的段。如果两个子程序没有直接或间接的调用关系，则他们可以被分配到同一个段中，反之则不能。换言之，当且仅当 $a$ 和 $b$ 在调用树上**不是祖先-后代关系**，$a$ 和 $b$ 可以被分配到同一个段中。

一个段的大小应当是所有分配到这个段的子程序所需内存大小的最大值，所有段大小的和不能超过系统的内存大小。

现在艾莉芬想要知道，电力控制芯片至少要有多少内存，才能保证春节十二响的正确运行。即：最少需要多大的内存，才能通过先**将内存分成若干个段**，再**把每个子程序分配到一个段中**，使得**每个段中分配的所有子程序之间不存在祖先-后代关系**。

# 输入格式

从标准输入读入数据。

第一行包含一个正整数 $n$ 表示子程序的个数，其中 $n\le 2\times 10^5$。

第二行有 $n$ 个用空格隔开的正整数 $M_1, M_2, \dots, M_n$，$M_i$ 表示第 $i$ 个子程序所需的内存空间。

第三行有 $n-1$ 个用空格隔开的正整数 $f_2, f_3, \dots, f_n$，满足 $f_i<i$，表示第 $i$ 个子程序在调用树上的父亲是第 $f_i$ 个子程序。

# 输出格式

输出到标准输出。

仅一个整数，表示最小的内存需求。

# 样例

#### 样例输入 1
```plain
5
10 20 20 30 30
1 1 2 2
```
#### 样例输出 1
```plain
60
```
#### 样例说明 1
在最优方案中，内存被划分为大小为 `10`，`20`，`30` 的三个段，其中第 $1$ 个子程序被分配在第 $1$ 个段中，第 $2$、$3$ 个子程序被分配在第 $2$ 个段中，第 $4$、$5$ 个子程序被分配在第 $3$ 个段中。可以证明，不存在更优的方案。

#### 样例 2
见附加文件中的 `2.in` 与 `2.ans`。

#### 样例 3
见附加文件中的 `3.in` 与 `3.ans`。

# 数据范围与提示

|测试点|$n$|$M$|是否是一条链|
|:-:|:-:|:-:|:-:|
|$1\sim 2$|$\le 5$|$\le 10$|否|
|$3\sim 4$|$\le 10$|$\le 2$|否|
|$5\sim 9$|$\le 16$|$\le 10^9$|否|
|$10\sim 12$|$\le 2\times 10^5$|$\le 10^9$|是|
|$13\sim 15$|$\le 2000$|$\le 10^9$|否|
|$16\sim 20$|$\le 2\times 10^5$|$\le 10^9$|否|

注意：在第 10、11、12 号测试点中，1 号子程序**不一定**是链的一个端点。

其中 $M$ 是所有子内存需求的最大值，即 $\max\{M_i\}$。

对于全部数据，$1\le n\le 2\times 10^5$，$1\le M\le 10^9$。

#### 提示
艾莉芬经过**仔细阅读题面、认真分析数据范围**后，开始编写程序求解这个问题。

```plain
$ login Elephant
password: ********
艾莉芬，高级程序员。豫阳市第三工程组提醒您：
- 做题千万条，读题第一条；
- 编程不规范，爆零两行泪。
$ cd spring
$ ac spring
Spring Accepted. Score: 100/100.
```
