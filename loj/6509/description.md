
# 题目描述

给定一棵 $n$ 个点的树，树上每个点初始有一个 $0$ 或 $1$ 的数字。

考虑这样一个过程：

1. 等概率随机选择一个点作为起点
2. 等概率随机选择一个新点并沿着树上的路径移动过去，最后反转这个新点上的数字（注意只反转这个新点上的数字而非经过的所有点的数字）
3. 如果此时整棵树上的所有数字相同，则过程结束；否则回到步骤 $2$

求出期望的移动距离，对 $10^9 + 7$ 取模。

# 输入格式

第一行一个整数 $n$。

第二行一个长度为 $n$ 的 $01$ 串，表示每个点的初始数字。

接下来 $n - 1$ 行，其中第 $i$ 行一个整数 $f$ 表示一条连接 $i + 1$ 和 $f$ 的边。

# 输出格式

一行一个整数表示答案。

# 样例

#### 样例输入 1
```plain
2
01
1
```

#### 样例输出 1
```plain
500000004
```

#### 样例解释 1

- 初始点为 $1$，选择的新点为 $1$，过程结束，距离为 $0$
- 初始点为 $1$，选择的新点为 $2$，过程结束，距离为 $1$
- 初始点为 $2$，选择的新点为 $2$，过程结束，距离为 $0$
- 初始点为 $2$，选择的新点为 $1$，过程结束，距离为 $1$

答案为 $\frac{1}{2}$，对 $10 ^ 9 + 7$ 取模等于 $500000004$。

#### 样例输入 2
```plain
3
001
1
1
```

#### 样例输出 2
```plain
638888896
```

#### 样例解释 2

一种可能的方案如下：

1. 从 $2$ 号点出发，选择了 $2$ 号点自己，这一步的移动步数为 $0$， $2$ 号点数字变为 $1$
2. 选择 $3$ 号点，这一步的移动步数为 $2$， $3$ 号点数字变为 $0$
3. 选择 $2$ 号点，这一步的移动步数为 $2$， $2$ 号点数字变为 $0$
4. 此时所有点均变为 $0$，过程结束，总移动步数为 $4$

最终答案为 $\frac{95}{36}$，对 $10^9 + 7$ 取模等于 $638888896$。

# 数据范围与提示

对于全部数据， $3 \leq n \leq 100000$，保证初始局面不满足终止条件。

- 存在 $10 \%$的数据， $n \leq 5$。
- 存在 $30 \%$的数据， $n \leq 20$。
- 存在 $50 \%$的数据， $n \leq 100$。
- 存在 $70 \%$的数据， $n \leq 1000$。

