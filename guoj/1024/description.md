
# 题目描述

九条可怜是一个热爱打麻将的女孩子。因此她出了一道和麻将相关的题目，希望这题不会让你对麻将的热爱消失殆尽。 

![110](source/guoj/1024/img/aHR0cDovL3d3dy53anl5eS50b3Avd3AtY29udGVudC91cGxvYWRzLzIwMTkvMDQvQ0ZaVFpaSEY0QkRUUUIucG5n.png)

今天，可怜想要打麻将，但是她的朋友们都去下自走棋了，因此可怜只能自己一个人打。可怜找了一套特殊的麻将，它有 $n(n\ge 5)$ 种不同的牌，大小分别为 $1$ 到 $n$，每种牌都有 $4$ 张。

定义面子为三张大小相同或者大小相邻的麻将牌，即大小形如 $i,i,i(1\le i\le n)$ 或者 $i,i+1,i+2(1\le i\le n-2)$。定义对子为两张大小相同的麻将牌，即大小形如 $i,i(1\le i\le n)$。

定义一个麻将牌集合 $S$ 是胡的当且仅当它的大小为 $14$ 且满足下面两个条件中的至少一个：

- $S$ 可以被划分成五个集合 $S_1$ 至 $S_5$。其中 $S_1$ 为对子，$S_2$ 至 $S_5$ 为面子。
- $S$ 可以被划分成七个集合 $S_1$ 至 $S_7$，它们都是对子，且对应的大小两两不同。

举例来说，下列集合都是胡的（这儿只标记了大小）：

- $\{1,1,1,1,2,3,4,5,6,7,8,9,9,9\}$
- $\{1,1,2,2,4,4,5,5,6,6,7,7,8,8\}$
- $\{1,1,2,2,3,3,4,4,5,5,6,6,7,7\}$


而下列集合都不是胡的：
- $\{1,1,1,2,3,4,5,6,7,8,9,9,9\}$
- $\{1,1,1,1,4,4,5,5,6,6,7,7,8,8\}$
- $\{1,1,1,2,3,4,5,6,7,8,9,9,9,11\}$

可怜先摸出了 $13$ 张牌，并把剩下的 $4n-13$ 张牌随机打乱。打乱是等概率随机的，即所有 $(4n-13)!$ 种排列都等概率出现。

对于一个排列 $P$，可怜定义 $S_i$ 为可怜事先摸出的 $13$ 张牌加上 $P$ 中的前 $i$ 张牌构成的集合，定义 $P$ 的权值为最小的 $i$ 满足 $S_i$ 存在一个子集是胡的。如果你对麻将比较熟悉，不难发现 $P$ 的权值就是理论上的最早胡牌巡目数。注意到 $n\ge 5$ 的时候，$S_{4n-13}$ 总是存在胡的子集的，因此 $P$ 的权值是良定义的。

现在可怜想要训练自己的牌效，因此她希望你能先计算出 $P$ 的权值的期望是多少。 

# 输入格式

第一行输入一个整数 $n$，表示这副特殊的麻将牌中的大小种类数。

接下来输入 $13$ 行每行两个整数 $w,t(1\le w\le n, 1\le t\le 4)$，表示可怜最开始摸出的第 $i$ 张牌是大小为 $w$ 的第 $t$ 张牌，保证 $(w,t)$ 二元组两两不同。 

# 输出格式

输出一行一个整数，表示答案对 $998244353$ 取模后的值。即如果答案的最简分数表示为 $\frac xy(x\ge 0,y\ge 1, \gcd(x,y)=1)$，你需要输出 $x\times y^{-1} \bmod 998244353$。

# 样例

## 样例输入

```plain
9
1 1
1 2
1 3
2 1
3 1
4 1
5 1
6 1
7 1
8 1
9 1
9 2
9 3 
```

## 样例输出
```plain
1
```

## 样例解释

上述牌型叫做纯正九莲宝灯，不难发现不管再加一张什么牌它都是胡的。所以对于所有排列 $P$，权值都是 $1$，因此权值的期望就是 $1$。

# 数据范围与提示

对于 $20\%$ 的数据，$n=5$。

对于 $50\%$ 的数据，$n\le 13$。

对于另外 $20\%$ 的数据，$n\le 100,w_i=i,t_i=1$。

对于另外 $20\%$ 的数据，$n\le 100,w_i =\left\lceil\frac i4\right\rceil,t_i=i \bmod 4+1$。

对于 $100\%​$ 的数据，$5\le n\le 100$。
