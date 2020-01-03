
# 题目描述

**题目译自 [POI XXVII - I etap](https://sio2.mimuw.edu.pl/c/oi27-1/dashboard/) 「[Najmniejsza wspólna wielokrotność](https://szkopul.edu.pl/problemset/problem/nYCgpBEkq_hw9S-QaoEOOKCI/site/)」**

给出一个自然数 $ M $，找到一个区间 $ [a,~b] $ 使得 $ M = \text{lcm}(a, a + 1, \dots, b) $，并且 $ a < b $。

# 输入格式

输入数据第一行包含一个整数 $ z $，表示测试数据组数。对于每组测试数据：

第一行包含一个整数 $ M $，含义如题面所述。

# 输出格式

对于每组数据，如果不能找到一个合法的区间，输出 `NIE`。否则，输出两个正整数 $a$ 和 $b$。如果存在多组解，找一个 $a$ 最小的。如果还有多组解，找一个 $b$ 最小的。

# 样例

#### 样例输入

```plain
3
12
504
17
```

#### 样例输出

```plain
1 4
6 9
NIE
```

### 样例解释

对于第一个数据，$12$ 是区间 $[2,4]$ 的最小公倍数，包含 $2$，$3$ 和 $4$。也是区间 $[1,4]$ 的最小公倍数，包含 $1$，$2$，$3$ 和 $4$。其中后者的 $a$ 更小。

附加样例参见 `nww/nww*.in` 和 `nww/nww*.out`：

+ 附加样例 $1$：$5$ 组数据，$M$ 依次为：$5$，$6$，$7$，$8$ 和 $9$；

+ 附加样例 $2$：$1$ 组数据，$M$ 为 $1\ 000\ 000$；

+ 附加样例 $3$：$1$ 组数据，$M$ 为 $99\ 999\ 990\ 000\ 000$；

+ 附加样例 $4$：$z = 10000$ ，$M$ 为 $500\ 001\ 500\ 001\ 000\ 001$ 和 $500\ 001\ 500\ 001\ 000\ 000$ 交替出现。

# 数据范围与提示

| Subtask # | 额外限制                         | 分值  |
|:---------:|:----------------------------:|:---:|
| 1         | $1 \le z \le 10, 1 \le M \le 1000$       | 18  |
| 2         | $1 \le z \le 100, 1 \le M \le 10^9$      | 20  |
| 3         | $1 \le z \le 100, 1 \le M \le 10^{18}$   | 20  |
| 4         | $1 \le z \le 10000, 1 \le M \le 10^{18}$ | 42  |
