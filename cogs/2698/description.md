# 题目描述


<h3>
【题目描述】
</h3>
<p>
在一条环形公路旁均匀地分布着$N$座仓库，编号为$1···N$，编号为 i 的仓库与编号为 j 的仓库之间的距离定义为$ dist(i,j)=min⁡(|i-j|,N-|i-j|)$，也就是逆时针或顺时针从 i 到 j 中较近的一种。每座仓库都存有货物，其中编号为 i 的仓库库存量为 $A_i$。在 i 和 j 两座仓库之间运送货物需要的代价为$ A_i+A_j+dist(i,j)$。求在哪两座仓库之间运送货物需要的代价最大。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数N，第二行N个整数A1~AN。
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数，表示最大代价。
</p>
<h3>
【样例输入】
</h3>
<pre>5
1 8 6 2 5
</pre>
<h3>
【样例输出】
</h3>
<pre>15
</pre>
<h3>
【提示】
</h3>
<p>
$1≤N≤10^6，1&lt;=A_i&lt;=10^7。$
</p>
<h3>
【来源】
</h3>
<p>
《算法竞赛进阶指南》
</p>
