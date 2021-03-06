# 题目描述


<p>
$Bessie$准备用从牛棚跑到池塘的方法来锻炼. 但是因为她懒,她只准备沿着下坡的路跑到池塘,然后走回牛棚.
</p>
<p>
$Bessie$也不想跑得太远,所以她想走最短的路经. 农场上一共有$M (1 &lt;= M &lt;= 10,000)$条路,每条路连接两个用$1..N(1 &lt;= N &lt;= 1000)$标号的地点. 更方便的是,如果$X&gt;Y$,则地点$X$的高度大于地点$Y$的高度. 地点$N$是$Bessie$的牛棚;地点$1$是池塘.
</p>
<p>
很快, $Bessie$厌倦了一直走同一条路.所以她想走不同的路,更明确地讲,她想找出$K (1 &lt;= K &lt;= 100)$条不同的路经.为了避免过度劳累,她想使这$K$条路径为最短的$K$条路径.
</p>
<p>
请帮助$Bessie$找出这$K$条最短路经的长度.你的程序需要读入农场的地图, 一些从$X_i$到$Y_i$的路径和它们的长度$(X_i, Y_i, D_i)$. 所有$(X_i, Y_i, D_i)$满足$(1 &lt;= Y_i &lt; X_i; Y_i &lt; X_i &lt;= N, 1 &lt;= D_i &lt;= 1,000,000).$
</p>
<p>
题目名称: cowjog
</p>
<p>
输入格式:
</p>
<ul>
<li>
第$1$行: 3个数: $N,M,K$
</li>
</ul>
<ul>
<li>
第$2..M+1$行: 第 $i+1 $行包含3个数 $X_i, Y_i,D_i$, 表示一条下坡的路.
</li>
</ul>
<p>
样例输入 (cowjog.in):
</p>
<pre>5 8 7
5 4 1
5 3 1
5 2 1
5 1 1
4 3 4
3 1 1
3 2 1
2 1 1
</pre>
<p>
输出格式:
</p>
<ul>
<li>
第$1..K$行: 第$i$行包含第$i$最短路径的长度,或$-1$如果这样的路径不存在.如果多条路径有同样的长度,请注意将这些长度逐一列出.
</li>
</ul>
<p>
样例输出 (cowjog.out):
</p>
<pre>1
2
2
3
6
7
-1
</pre>
<p>
输出解释:
</p>
<p>
路径分别为$(5-1), (5-3-1), (5-2-1), (5-3-2-1), (5-4-3-1),(5-4-3-2-1)$
</p>
