
# 题目描述

众所周知 Kimo·Amnesia·Yami 只有 $7$ 分钟的记忆，但 Yami 仍坚持研究各种问题。现在，他在潜心研究错位排序问题。

一个 $1\sim n$ 的排列 $p_i$ 是错位的当且仅当对于 $\forall i$ 都有 $p_i \neq i$。

Yami 发现这个问题有些难度，于是开始尝试暴力枚举... ...

他拿出草稿纸一看，发现上面已经有了一个长度为 $n$ 的数列 $\{a_n\}$。

过了一段时间，Yami 发现了这个数列的两个性质：

1. 对于 $\forall i$  都有 $a_i \neq i$。 
2. 若 $a_i = a_j$ 且 $i \neq j$ 则必有 $a_i = a_j = 0$。

这时，Yami 想到了这样一个问题：如果把数列 $\{a_n\}$ 中所有的 $0$ 换成 $1\sim n$ 中的其他数字，有多少不同的方法使得改变后的 $\{a_n\}$ 是一个 $1\sim n$ 的错位排列？

两个改变后的序列 $\{a_n\}$ 与 $\{a^{\prime}_n\}$ 是不同的当且仅当 $\exists i$ 使得 $a_i \neq a^{\prime}_i$。

由于答案可能很大，请输出答案除 $ 10^9 + 7$ 后的余数即可。


# 输入格式

第一行一个正整数 $T(1\leq T \leq 10)$ 代表测试数据组数。

每组测试数据第一行一个正整数 $n(1 \leq n \leq 10^5)$ 代表数列长度。

下面一行 $n$ 个正整数 $a_i(0 \leq a_i \leq n)$ 且 $a_i$ 满足题目中描述的两个性质。

# 输出格式

共 $T$ 行，每行一个非负整数代表可能变换出的错位排列的个数对 $10^9 + 7$ 取模。

# 样例

#### 样例输入

```plain
2
5
2 0 0 0 0
8
0 3 0 0 4 0 0 0
```

#### 样例输出

```plain
11
362
```

# 数据范围与提示



