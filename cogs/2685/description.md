# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
小钟、小皓和小曦都是著名偶像派OI选手，他们都有很多迷妹。
</p>
<p>
现在，有n个妹子排成了一行，从左到右编号为1到n。这些妹子中，任意一个都是其中一个人的迷妹。
</p>
<p>
现在，蒟蒻wyz有Q个问题，第i个问题为：编号在l[i]到r[i]范围内的妹子中，分别有几个小钟的迷妹、小皓的迷妹、和小曦的迷妹。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入到fans.in
</p>
<p>
第一行2个正整数n,Q。
</p>
<p>
第2行到第n+1行每行一个正整数a[i]，描述了第i个妹子是谁的迷妹。a[i]=1表示小钟的迷妹，a[i]=2表示小皓的迷妹，a[i]=3表示小曦的迷妹。
</p>
<p>
第n+2行到第n+Q+1行，每行2个整数，表示第i个问题。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出到fans.out
</p>
<p>
共Q行，每行3个用空格分开的整数，分别表示对于第i个问题，有多少小钟、小皓、小曦的迷妹。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
6 3
</p>

<p>
2
</p>

<p>
1
</p>

<p>
1
</p>

<p>
3
</p>

<p>
2
</p>

<p>
1
</p>

<p>
1 6
</p>

<p>
3 3
</p>

<p>
2 4
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
3 2 1
</p>

<p>
1 0 0
</p>

<p>
2 0 1
</p>
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
【数据范围】
</p>
<p>
对于10%的数据，保证1&lt;=n&lt;=10，Q&lt;=10，
</p>
<p>
对于25%的数据，保证1&lt;=n&lt;=100，Q&lt;=100，
</p>
<p>
对于45%的数据，保证1&lt;=n&lt;=1000，Q&lt;=1000，
</p>
<p>
对于100%的数据，保证1&lt;=n&lt;=100,000，Q&lt;=100,000。
</p>
<p>
保证1&lt;=a[i]&lt;=3，1&lt;=l[i]&lt;=r[i]&lt;=n。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
QBXT2017春令营第一次测试T1
</p>
