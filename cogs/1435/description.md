# 题目描述


<h3>
【题目描述】
</h3>
<p>
你可能已经听说了金发姑娘和3只熊的经典故事。
</p>
<p>
鲜为人知的是，金发姑娘最终经营了一个农场。在她的农场，她有一个谷仓含N头奶牛（1&lt;=N &lt;= 20000)。不幸的是，她的奶牛对温度相当敏感。
</p>
<p>
第i头奶牛必须在指定的温度范围内A(i)..B(i)才感觉舒适；（0&lt;=A(i)&lt;=B(i)&lt;= 1,000,000,000）。如果金发姑娘在谷仓放置一个温控器；如果温度T&lt;A(i)，牛会太冷，并将产生x单位牛奶。如果她把恒温器调到（A(i)&lt;=T&lt;=B(i)）这个范围内,那么牛会感到舒适，并将产生Y单位牛奶。如果她把恒温器调到温度T&gt;B(i)，牛会感觉很热，并将产生的Z单位牛奶。正如预期的那样，Y的值总是大于X和Z。
</p>
<p>
给定的X，Y，和Z，以及每个牛的温度的最佳范围，如果金发姑娘设置谷仓的温控器最佳，请计算金发姑娘得到牛奶的最大数量，已知X，Y和Z都是整数，范围0..1000。温控器可以设置为任意整数的值。
</p>
<h3>
【输入格式】
</h3>
<p>
第1行：四个用空格隔开的整数：N X Y Z。
</p>
<p>
第2行..1 + N：行1+i包含两个用空格隔开的整数：A(i)和B(i)。
</p>
<h3>
【输出格式】
</h3>
<p>
1行：金发姑娘最多可以获得的牛奶，当她在谷仓的最佳温度设定。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
4 7 9 6
5 8
3 4
13 20
7 10
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>31</pre>
<h3>
【提示】
</h3>
<p>
在农场里有4头奶牛，温度范围5..8，3..4，13..20，10..7。一个寒冷的奶牛生产7单位的牛奶，一个舒适的奶牛生产9个单位的牛奶，一个热牛生产6单位牛奶。
</p>
<h3>
【数据规模】
</h3>
<p>
50%的测试数据：n&lt;=5
</p>
<p>
其余50%的测试数据：10000&lt;n&lt;=20000.
</p>
<h3>
【来源】
</h3>
<p>
USACO 2013 November Contest, Bronze
</p>
<p>
translate by cqw
</p>
<p>
data from cstdio
</p>
