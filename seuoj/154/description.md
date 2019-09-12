
# 题目描述

三种颜色的岛屿分别有 $a$ 座，$b$ 座，$c$ 座，现在要求在岛屿中修建一些边权为 $1$ 的桥，要求任意两个相同颜色的岛屿要么不相通，要么这两座岛屿之间的最短路大于等于 $3$ 。计算总方案数除 $998244353$ 所得的余数。

# 输入格式

第一行仅有一个数字 $T(1\le T \le 10)$，代表数据组数。下面依次是每一组数据

每组数据仅有一行三个数字 $a,b,c(1\le a,b,c\le 5000)$。

# 输出格式

每组数据一行一个整数，代表总方案数除 $998244353$ 所得的余数。

# 样例

#### 样例输入

```plain
4
1 1 1
1 2 2
1 3 5
6 2 9
```

#### 样例输出

```plain
8
63
3264
813023575
```

# 数据范围与提示


