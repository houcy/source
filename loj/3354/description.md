
# 题目描述

**题目译自 [BalticOI 2017](http://www.boi2017.org/) Day1「[Political Development](http://www.boi2017.org/wp-content/uploads/2017/05/tasks-en.pdf)」**

某个有 $n$ 个成员的政党想要发展一些全新的政策。为了做到这一点，这个政党将会建立一个委员会。显然，当所有委员会委员的意见都不一致，并且这个委员会尽量大的时候，政策得以最好地发展。  
为了指出哪一对政治家的意见不一致以及哪一对意见一致，政党安排每一对可能的政治家讨论一个随机选择的话题。无论何时，如果两个政治家不能在指定的话题上达成统一意见，这件事情就会被记录在政党的功德册上。  
带着这本功德册，你被指派去完成找出最大的委员会，使得所有的委员的意见都不一致的任务。然而，找到一个大的委员会是非常有挑战的。仔细的分析结果显示，对于任意一个由党员所组成的非空的小组，至少存在一个小组成员，使得小组中与他的意见不一致的成员严格少于 $k$ 个。那么显然委员会不能有多于 $k$ 个成员。但是能够选出一个这个大小的委员会吗？找到最大的委员会的大小，使得其中没有人的意见是一致的。

---

#### 一句话题意

给出一张无向图，满足对于任意导出子图，存在一个节点的度数小于 $k$，求原图的最大团。

# 输入格式

第一行包含两个整数 $n$ 和 $k$，$n$ 表示政党成员的人数，$k$ 如上所述。  
每个成员用一个 $0$ 到 $n-1$ 之间的整数 $i$ 表示。  
接下来的 $n$ 行，每行描述一个成员 $i$，从 $i=0$ 开始。描述成员 $i$ 的行以一个整数 $d_i$ 开始，接下来是 $d_i$ 个整数，表示与第 $i$ 个成员意见不同的成员编号。

# 输出格式

输出仅一行一个整数，表示最大的委员会成员数。

# 样例

#### 样例输入 1

```
5 3
2 1 2
3 0 2 3
3 0 1 4
2 1 4
2 2 3
```

#### 样例输出 1

```
3
```

#### 样例输入 2

```
5 3
3 1 2 4
1 0
1 0
0
1 0
```

#### 样例输出 2
```
2
```

# 数据范围与提示

对于 $100\%$ 的数据，$0 \le d_i<n\le 5 \times 10^4$，$1 \le k \le 10$。

详细子任务与附加限制如下：

- Subtask 1（4 pts）：$k \le 2$，$n \le 5 \times 10^3$。
- Subtask 2（12 pts）：$k \le 3$，$n \le 5 \times 10^3$。
- Subtask 3（23 pts）：$d_i \le 10$。
- Subtask 4（38 pts）：$n \le 5 \times 10^3$。
- Subtask 5（23 pts）：$ k \le 5$。

