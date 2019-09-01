
# 题目描述

在这世上有一乡一林一竹亭，也有一主一仆一仇敌。

有人曾经想拍下他们的身影，却被可爱的兔子迷惑了心神。

那些迷途中的人啊，终究会消失在不灭的永夜中……  

---

蓬莱山 辉夜 (Kaguya) 手里有一堆数字。

辉夜手里有 $n$ 个非负整数 $a_1,a_2\cdots a_n$，由于辉夜去打 Gal Game 去了，她希望智慧的你来帮忙。  

* 你需要将这些数分成若干组，满足 $n$ 个数中的每一个数都恰好被分到了一个组中，且每一组至少包含一个数。  

定义一组数的权值为该组内所有数的**异或和**。请求出一种分组方案，使得分出的所有组数的权值之和最小，输出权值之和的最小值。

# 输入格式

输入的第一行包含一个正整数 $n$，表示给定的非负整数的数量。

接下来一行包含 $n$ 个非负整数$a_1,a_2\cdots a_n$。

# 输出格式

输出一行一个整数表示答案。

# 样例

##### 样例输入 1

```plain
3
1 2 5
```

#### 样例输出 1

```plain
6
```

#### 样例解释 1

一种最优的分组方案如下：

- 将第 $1$ 个数和第 $3$ 个数分为一组，该组的权值为 $1\oplus 5 = 4$
- 将第 $2$ 个数分为一组，该组的权值为 $2$

该分组方案的所有组的权值之和为 $4 + 2 = 6$，可以证明，不存在权值之和更小的分组方案。

#### 样例输入 2

```plain
6
9 18 36 25 9 32
```

#### 样例输出 2

```plain
15
```

#### 样例解释 2

一种最优的分组方案如下：

- 将第 $1$ 个数和第 $5$ 个数分为一组，该组的权值为 $9\oplus 9 = 0$
- 将第 $2$ 个数和第 $4$ 个数分为一组，该组的权值为 $18\oplus 25 = 11$
- 将第 $3$ 个数和第 $6$ 个数分为一组，该组的权值为 $36\oplus 32 = 4$

该分组方案的所有组的权值之和为 $0 + 11 + 4 = 15$。可以证明，不存在权值之和更小的分组方案。

# 数据范围与提示

#### 子任务

对于 $80\%$ 的数据，满足 $n\leq 15$。

对于 $100\%$ 的数据，满足 $n\leq 10^6,a_i \leq 10^9$。

#### 题目来源

[迷途之家 2019 联赛](https://www.luogu.org/contest/20135) (MtOI2019) T1

出题人：disangan233


