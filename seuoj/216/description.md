
# 题目描述

4qwerty7 在讲 Splay 时为了方便，把节点父亲的父亲称为“爷爷”，这引发了他的进一步思考：

在一棵树上任选 $4$ 个节点，前两个的 LCA 与 后两个的 LCA 的 LCA 的标号的期望是多少？

我们可以对该问题做如下形式化的表述：

给定一棵 $n$ 个节点的有根树，将根节点标号 $1$，将其他节点标号 $2\sim n$，标号为 $i$ 为节点记作 $v_i$，记 $getId(v_i)=i$，求 $E[getId(lca(lca(v_A,v_B),lca(v_C,v_D))]$。

其中 $A,\ B,\ C,\ D$ 为四个相互独立离散型随机变量，$P(A=i)=P(B=i)=P(C=i)=P(D=i)=\frac1n,\ i=1,2,3,\ldots,n$。

上文 $P(X)$ 表示事件 $X$ 发生的概率，$E[X]$ 表示随机变量 $X$ 的数学期望，$lca(x,y)$ 表示 $x,\ y$ 两节点的最近公共祖先节点，即两节点祖先节点集合的交中深度最大的节点。

我们定义一个结点的祖先节点集合即从根节点到该结点的所经分支上的所有结点（含根与该节点自身）的集合，一个节点的深度即它祖先节点集合的大小。

# 输入格式

输入数据第一行有一个整数 $T(1\leq T\leq 10)$，表示测试数据组数，接下来为各组测试数据。

对于每组测试数据，第一行为一个整数 $n(1\leq n\leq 10^5)$，表示树的节点数目，接下来 $n$ 行每行两个整数 $x,\ y(1\leq x,y\leq n)$ 表示标号为 $x$ 与标号为 $y$ 的节点间有一条边，数据保证给出的边中仅有一条重复出现，且仅重复两次。

# 输出格式

对于每组测试数据，输出一行一个整数，表示所求期望与 $n^4$ 的乘积。

答案可能很大，请注意各种整数类型的数据范围，C++ 下推荐使用 `__int128`。

# 样例

#### 样例输入

```plain
1
5
2 1
3 2
4 2
5 1
2 3
```

#### 样例输出

```plain
713
```

# 数据范围与提示


