# 题目描述


<h3>
【题目描述】
</h3>
<p>
雪甜甜公主从小聪颖过人，喜欢玩一个”组合数游戏&#34;。
</p>
<p>
是这样玩的： 给出n个数，雪甜甜公主会从里面随机地选出[0, n]个数(同一个位置上的数不能重复选)，加起来得到一个结果。如果她一个数都没选结果就是0
</p>
<p>
雪甜甜公主不愧是雪甜甜公主，玩得次数多了后似乎发现了一些规律。于是她现在想知道，
</p>
<p>
她随机组合出来的结果， 在[l, r]范围内的概率是多大？
</p>
<p>
(不要吐槽题目名字combination拼错了，造数据的时候打错个字母懒得改了= =)
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个正整数n
</p>
<p>
第二行n个正整数，是雪甜甜公主正在玩的这n个数。
</p>
<p>
第三行，两个正整数，l, r。
</p>
<h3>
【输出格式】
</h3>
<p>
一行，一个浮点数。四舍五入精确到小数点后4位数字。
</p>
<h3>
【样例】
</h3>
<pre>#input1 </pre>
<pre>12
1 2 3 4 5 6 1 2 3 4 5 6
0 42</pre>
<pre>#output1</pre>
<pre>1.000
</pre>
<pre>#input2</pre>
<pre>12
1 2 3 4 5 6 1 2 3 4 5 6
12 33</pre>
<pre>#output2</pre>
<pre>0.8870
</pre>
<h3>
【提示】
</h3>
对于前55%的数据满足 n &lt;= 20
对于之后的数据 n &lt;= 45
对于100%的数据 这n个数a1, a2.. an &lt;= 100， 0 &lt;= l &lt;= r &lt;= sum{a}
<h3>
【来源】
</h3>
http://syzoj.com/problem/278
