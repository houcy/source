# 题目描述


<h3>
【题目描述】
</h3>
<p>
万有引力定律：
</p>
<p>
“使物体相互靠近的力的大小与物体的质量成正比——而物体的质量又由同一种力决定。这是一个有趣并且有益的例子，说明了科学是如何用A证明B，再用B证明A的。”——安布罗斯·比尔斯（美国讽刺作家——译者注）。
</p>
<p>
<br/>
</p>
<p>
你有一坨K个毛球（&lt;星际迷航&gt;中的种族——译者注）。这种毛球只会存活一天。在死亡之前，一个毛球有P_i的概率生出i个毛球(i=0,1,...,n-1)。m天后所有毛球都死亡的概率是多少？（包含在第m天前全部死亡的情况）
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。
</p>
<p>
输入文件的第1行是一个正整数N，表示数据组数。
</p>
<p>
每组数据的第1行有3个正整数n(1&lt;=n&lt;=1000),k(0&lt;=k&lt;=1000),m(0&lt;=m&lt;=1000)。
</p>
<p>
接下来有n行，给出P_0,P_1,...,P_n-1。
</p>
<h3>
【输出格式】
</h3>
<p>
对于第i组数据，输出&#34;Case #i: &#34;，后面是第m天后所有毛球均已死亡的概率。
</p>
<h3>
【样例输入】
</h3>
<pre>4
3 1 1
0.33
0.34
0.33
3 1 2
0.33
0.34
0.33
3 1 2
0.5
0.0
0.5
4 2 2
0.5
0.0
0.0
0.5
</pre>
<h3>
【样例输出】
</h3>
<pre>Case #1: 0.3300000
Case #2: 0.4781370
Case #3: 0.6250000
Case #4: 0.3164063
</pre>
<h3>
【提示】
</h3>
<p>
如果你的输出与标准答案相差不超过10^-5，那么你的答案就被认为是正确的。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=481&amp;page=show_problem&amp;problem=1962" target="_blank">UVa11021 Tribles</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2.8
</p>
