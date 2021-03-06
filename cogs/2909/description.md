# 题目描述


<h3>
【题目描述】
</h3>
<p>
Farmer John最讨厌的农活是运输牛粪。为了精简这个过程，他产生了一个新奇的想法：与其使用拖拉机拖着装满牛粪的大车从一个地点到另一个地点，为什么不用一个巨大的便便弹弓把牛粪直接发射过去呢？（事实上，好像哪里不太对……）
</p>
<p>
Farmer John的农场沿着一条长直道路而建，所以他农场上的每个地点都可以简单地用该地点在道路上的位置来表示（相当于数轴上的一个点）。FJ建造了$N$个弹弓（$1≤N≤10^5$），其中第ii个弹弓可以用三个整数$x_i$，$y_i$以及$t_i$描述，表示这个弹弓可以在$t_i$单位时间内将牛粪从位置$x_i$发射到位置$y_i$。
</p>
<p>
FJ有$M$堆牛粪需要运输（$1≤M≤10^5$）。第$j$堆牛粪需要从位置$a_j$移动到位置$b_j$。使用拖拉机运输牛粪，经过路程$d$需要消耗$d$单位时间。FJ希望通过对每一堆牛粪使用至多一次弹弓来减少运输时间。FJ驾驶没有装载牛粪的拖拉机的时间不计。
</p>
<p>
对这$M$堆牛粪的每一堆，在FJ可以在运输过程中使用至多一次弹弓的条件下，帮助FJ求出其最小运输时间。
</p>
<h3>
【输入格式】
</h3>
<p>
输入的第一行包含$N$和$M$。下面$N$行，每行用$x_i$，$y_i$，$t_i$（$0≤x_i,y_i,t_i≤10^9$）描述了一个弹弓。最后$M$行用$a_j$和$b_j$描述了需要移动的牛粪。
</p>
<h3>
【输出格式】
</h3>
<p>
输出$M$行，每堆牛粪一行，表示运输这堆牛粪需要的最短时间。
</p>
<h3>
【样例输入】
</h3>
<pre>2 3
0 10 1
13 8 2
1 12
5 2
20 7
</pre>
<h3>
【样例输出】
</h3>
<pre>4
3
10
</pre>
<h3>
【提示】
</h3>
<p>
在这里，第一堆牛粪需要从位置1移动到位置12。不使用弹弓的话，会消耗11单位时间。但是，如果使用第一个弹弓，只需消耗1单位时间移动到位置0（弹弓的发射点），1单位时间将弹弓通过空中弹射并着陆在位置10（弹弓的目的地），然后2单位时间把牛粪移动到位置12。第二堆牛粪的最佳移动方案是不使用弹弓，第三堆牛粪应该使用第二个弹弓。
</p>
<h3>
【来源】
</h3>
<p>
USACO Feb18 Platinum Slingshot
</p>
<p>
供题：Brian Dean
</p>
