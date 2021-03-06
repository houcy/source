# 题目描述


<h3>
【题目描述】
</h3>
<p>
Bessie 正在玩捉迷藏游戏。（捉迷藏是这样玩的：在制定了奖罚规则后，玩家分为“捉”和“藏”两种，“藏”者有多个，在他们都藏起来后，由单独的一个“捉”者去找他们，这个游戏玩起来真是其乐无穷！）<br/>
Bessie 正在盘算她要藏到哪个牛棚里，一共有 $N(2\le N\le 20,000)$ 个牛棚，编号为 $1～N$。她知道“捉”者 FJ 会从 $1$ 号牛棚开始找。有 $M(1\le M\le 50,000)$ 条无向通路连接着所有的牛棚，其中通路 $i$ 的两个端点分别为 $A_i$ 和 $B_i$（$1\le A_i\le N$；$1\le B_i\le N$；$A_i≠B_i$），任意两个牛棚之间都可互达。<br/>
Bessie 觉得藏到跟 $1$ 号牛棚距离最远的牛棚里会比较安全，（这里两个牛棚之间的距离是指从一个牛棚到另一个牛棚的最短路径），请帮 Bessie 算一下最佳躲藏位置。
</p>
<h3>
【输入格式】
</h3>
<p>
第 $1$ 行：两个空格隔开的整数 $N,M$；
</p>
<p>
第 $2～M+1$ 行：第 $i+1$ 行有两个整数 $A_i,B_i$，即第 $i$ 条路的两个端点；
</p>
<h3>
【输出格式】
</h3>
<p>
一行，三个空格隔开的整数，分别为：离 $1$ 号牛棚最远的牛棚编号（如果最远的有多个，输出编号最小的那个）；最远的牛棚与 $1$ 号牛棚的最短路径；拥有此最短路径的牛棚个数。
</p>
<h3>
【样例输入】
</h3>
<pre>6 7
3 6
4 3
3 2
1 3
1 2
2 4
5 2
</pre>
<h3>
【样例输出】
</h3>
<pre>4 2 3
</pre>
<h3>
【提示】
</h3>
<p>
输入数据如图所示：
</p>
<p>
1--2--5
</p>
<p>
| /|
</p>
<p>
|/ |
</p>
<p>
3--4
</p>
<p>
|
</p>
<p>
6
</p>
<p>
4，5，6号牛棚距1号牛棚的最短路径均为2，选4号输出是因为它的编号最小。
</p>
