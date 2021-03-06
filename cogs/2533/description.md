# 题目描述


<h3>
【题目描述】
</h3>
<p>
Sky_miner的生日到了！
</p>
<p>
为了庆祝Sky_miner的生日，Sky_miner去抓鱼啦！
</p>
<p>
Sky_miner来到了平静的大海上，一个大海可以理解为一个二维平面。
</p>
<p>
Sky_miner在大海上撒下了一张渔网，一张渔网可以理解为一个于坐标轴平行的矩形
</p>
<p>
Sky_miner通过在海边架起的心灵监控器得知了小鱼的运动方式及时间，可是Sky_miner不知道到底什么时候收网才能获得最多的鱼。所以就有你来帮忙了！
</p>
<p>
Sky_miner从海边的心灵监控仪处获得了一系列小鱼移动的信息，每一条信息如下：
</p>
<p>
move in x-area l r d
</p>
<p>
move in y-area l r d
</p>
<p>
表示全球 $id$ 在 $l,r$ 之间的鱼向x(y)轴正方向移动了 $d$ 个单位长度。由于心灵控制器的存在，$d$ 恒大于零。
</p>
<p>
但是sky_miner蒙了，他不知道什么时候收网能获得多少鱼，所以这就交给你了。
</p>
<p>
Sky_miner的询问如下:
</p>
<p>
$query\ l\ r$ 表示询问全球 $id$ 在 $l,r$ 之间的鱼有多少鱼在网中（包括渔网边界）
</p>
<h3>
【输入格式】
</h3>
<p>
多组测试数据：
</p>
<p>
第一行一个整数 $T$，表示测试数据的组数。
</p>
<p>
对于每组测试数据，第一行一个正整数 $n$，表示鱼的数量。
</p>
<p>
接下来一共有 $n$ 行，每一行包括两个整数 $x_i,y_i$，第 $i+1$ 行表示全球 $id$ 为 $i$ 的鱼的初始坐标。
</p>
<p>
下面一行四个正整数 $x_1,y_1,x_2,y_2$ 分别表示渔网左下角的坐标和右上角的坐标
</p>
<p>
然后一行一个正整数 $m$，表示操作的总次数。
</p>
<p>
每个操作将会被如下形式给出:
</p>
<p>
$1\ l\ r\ d$ 表示 $id$ 在 $[l,r]$ 这个区间内的鱼向x轴正方向游动了d个单位长度。
</p>
<p>
$2\ l\ r\ d$ 表示 $id$ 在 $[l,r]$ 这个区间内的鱼向y轴正方向游动了d个单位长度。
</p>
<p>
$3\ l\ r$ 表示询问现在 $id$ 在 $[l,r]$ 这个区间内的鱼有多少在渔网内
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一个询问，输出询问的答案
</p>
<h3>
【样例输入】
</h3>
<pre>1
5
1 1 5 5
1 1
2 2
3 3
4 4
5 5
3
3 1 5
1 2 4 2
3 1 5
</pre>
<h3>
【样例输出】
</h3>
<pre>5
4
</pre>
<h3>
【提示】
</h3>
<p>
数据范围：
</p>
<p>
$1\le n,m\le 100000$
</p>
<p>
$1\le l\le r\le n$
</p>
<p>
$1\le d\le 10^9$
</p>
<p>
$x_1\le x_2,y_1\le y_2$
</p>
<p>
保证任意时刻的坐标绝对值不超过 $10^9$。
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2016
</p>
