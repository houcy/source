
# 题目描述

丢丢陈要安排他接下来 $n$ 天的生活，他每天可以休息，打比赛或者去锻炼。他知道接下来 $n$ 天的信息，每天会有四种情况。

0、体育馆不开门，网络上没有比赛。

1、体育馆不开门，网络上有比赛。

2、体育馆开门，网络上没有比赛。

3、体育馆开门，网络上有比赛。

丢丢陈不想连续两天打比赛，或者连续两天锻炼（但是可以连续两天休息）。

由于丢丢陈很懒，请你帮他安排一个休息天数最少的计划。

# 输入格式

第一行仅有一个数字 $T(1\le T\le 10)$ 代表数据组数。下面依次是每一组数据

每组数据两行，第一行一个整数 $n(1\le n\le 100)$，代表总天数。

第二行 $n$ 个整数 $a_i(0 \le a_i \le 3)$ 代表每一天的情况。

# 输出格式

每组数据一行一个数字，表示最小休息天数。

# 样例

#### 样例输入

```plain
3
4
1 3 2 0
7
1 3 3 2 1 2 3
2
2 2
```

#### 样例输出

```plain
2
0
1
```

# 数据范围与提示



