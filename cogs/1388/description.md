# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
有n个排成一圈的格子，并且已知正整数k和m，你需要往每个格子中填入一个大于等于k的正整数。将相邻的一些格子（或一个单独的格子）中的数加起来，可以产生一个新的数。
</p>
<p>
假设使用格子中的数可以产生出m,m+1,…,i，但不能产生i+1。求出往格子中填入哪些数，可以使得i尽量大。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
三行，每行一个正整数，分别为n,m,k。（k&lt;=m）
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
第一行一个正整数，表示最大的i。
</p>
<p>
下面若干行，每行为一个使i最大的填数方案，按照字典序升序排列。每行n个正整数a1,a2,…,an，表示依次往格子中填入的数，其中a1是n个数中最小的数。
</p>
<p>
注意，（1,1,2,3），（1,3,2,1），（1,2,3,1），（1,1,3,2）被认为是不同的方案，都需要输出。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>5
2
1</pre>
<h3>
【样例输出】
</h3>
<pre>21
1 3 10 2 5
1 5 2 10 3
2 4 9 3 5
2 5 3 9 4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
30%的数据中，n&lt;=5。
</p>
<p>
100%的数据中，n&lt;=6，k&lt;=m&lt;=20。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
