
# 题目描述

**译自 [COCI 2018/2019 Contest #3](https://hsin.hr/coci/archive/2018_2019/) T4「[NLO](https://hsin.hr/coci/archive/2018_2019/contest3_tasks.pdf)」**

Žabnik 村已经被不明飞行物（UFO）所创造的麦田怪圈所困扰了数年。其问题主要在夏季割草的时候显现出来。

麦田是一块 $N$ 行 $M$ 列的格子——左上角记为坐标 $(1,1)$，右下角记为坐标 $(N,M)$。一开始每块地上都有一单位的草。接下来 $K$ 天，圆形的 UFO 会登录在草地上并产生一个圆圈。第 $i$ 天早晨，一个半径为 $R_i$ 的 UFO 会登陆与位于 $(X_i, Y_i)$ 的草地上然后将其覆盖范围内的草都“割平”。或者说，如果一块坐标为 $(x,y)$ 的地满足 $(X_i-x)^2 + (Y_i-y)^2 \le R_i^2$，那么这块地的草的数量就会被归为 $0$。每过一天，每块草地的数量增加 $1$。

在第 $K$ 天晚上，当地人会将剩余的草全部收割，请问他们收割的草总量是多少？

# 输入格式

第一行两个正整数 $N,M$ 表示草地的行数和列数。

第二行一个正整数 $K$ 表示有 UFO 经过的天数。

接下来 $K$ 行，其第 $i$ 行包含三个正整数 $X_i, Y_i, R_i$，表示 UFO 登陆的位置以及半径。

# 输出格式

一个整数，输出收割的草的总量。

# 样例

#### 样例输入 1

```plain
6 6
3
4 4 2
3 3 2
2 4 1
```

#### 样例输出 1

```plain
68
```

#### 样例解释 1

第一天结束后：

```plain
1 1 1 1 1 1
1 1 1 0 1 1
1 1 0 0 0 1
1 0 0 0 0 0
1 1 0 0 0 1
1 1 1 0 1 1
```

第二天结束后：

```plain
2 2 0 2 2 2
2 0 0 0 2 2
0 0 0 0 0 2
2 0 0 0 1 1
2 2 0 1 1 2
2 2 2 1 2 2
```

第三天结束后：

```plain
3 3 1 0 3 3
3 1 0 0 0 3
1 1 1 0 1 3
3 1 1 1 2 2
3 3 1 2 2 3
3 3 3 2 3 3
```

#### 样例输入 2

```plain
100 100
2
50 50 49
30 30 29
```

#### 样例输出 2

```plain
9534
```

#### 样例输入 3

```plain
33333 44444
1
11111 22222 9999
```

#### 样例输出 3

```plain
1167355751
```


# 数据范围与提示

对于 $20\%$ 的数据，保证 $N, M \le 1000$。

对于 $100\%$ 的数据，保证：
- $1\le N, M \le 10^5$
- $1\le K \le 100$
- $1 < X_i < N$
- $1 < Y_i < M$
- $1 \le R_i \le \min(X_i - 1, Y_i - 1, N - X_i, M - Y_i)$


