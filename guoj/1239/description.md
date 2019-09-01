
# 题目描述

小 H 发誓要做 21 世纪最伟大的数学家。他认为，做数学家与做歌星一样，第一步要作好包装，不然本事再大也推不出去。为此他决定先在自己的住所上下功夫，让人一看就知道里面住着一个“未来的大数学家”。

为了描述方便，我们以向东为 $x$ 轴正方向，向北为 $y$ 轴正方向，建立平面直角坐标系。小 $H$ 的小屋东西长为 $100\mathrm{Hil}$（$\mathrm{Hil}$ 是小 H 自己使用的长度单位，至于怎样折合成“$\mathrm m$”，谁也不知道）。东墙和西墙均平行于 $y$ 轴，北墙和南墙分别是斜率为 $k_1$ 和 $k_2$ 的直线，$k_1$ 和 $k_2$ 为正实数。北墙和南墙的墙角处有很多块草坪，每块草坪都是一个矩形，矩形的每条边都平行于坐标轴。相邻两块草坪的接触点恰好在墙上，接触点的横坐标被称为它所在墙的“分点”，这些分点必须是 $1$ 到 $99$ 的整数。

小 H 认为，对称与不对称性的结合才能充分体现“数学美”。因此，在北墙角要有 $m$ 块草坪，在南墙角要有 $n$ 块草坪，并约定 $m\le n$。如果记北墙和南墙的分点集合分别为 $X_1$，$X_2$，则应满足 $X_1\subseteq X_2$，即北墙的任何一个分点一定是南墙的分点。

由于小 H 目前还没有丰厚的收入，他必须把草坪的造价降到最低，即草坪的占地总面积最小。你能编程帮他解决这个难题吗？


# 输入格式

仅一行，包含 $4$ 个数 $k_1$，$k_2$，$m$，$n$。$k_1$ 和 $k_2$ 为正实数，分别表示北墙和南墙的斜率，精确到小数点后第一位。$m$ 和 $n$ 为正整数，分别表示北墙角和南墙角的草坪的块数。

# 输出格式

一个实数，表示草坪的最小占地总面积。精确到小数点后第一位。

# 样例

#### 样例输入
```plain
0.5 0.2 2 4
```

#### 样例输出
```plain
3000.0
```

#### 样例解释
![](source/guoj/1239/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDYvMjEvNWQwYzhhZDEwZmVhNDMyNjU2LmpwZw==.jpg)



# 数据范围与提示

#### 约定
- 对于所有数据，$2\le m\le n\le 100$
- 南北墙距离很远，不会出现南墙草坪和北墙草坪重叠的情况

#### 评分标准
对于每个测试点，如果你的结果与标准答案的误差不超过 $0.1$，则可以得到该测试点的满分，否则得 $0$ 分。
