# 题目描述


<h3>
【题目描述】
</h3>
<p>
超市里有N件商品，每个商品都有利润$p_i$和过期时间$d_i$,每天只能卖一件商品，过期商品（即当天$d_i$&lt;=0）不能再卖。
</p>
<p>
求合理安排每天卖的商品的情况下，可以得到的最大收益是多少。
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组测试用例。
</p>
<p>
每组测试用例，以输入整数$N$开始，接下里输入$N$对$p_i$和$d_i$，分别代表第i件商品的利润和过期时间。
</p>
<p>
在输入中，数据之间可以自由穿插任意个空格或空行，输入至文件结尾时终止输入，保证数据正确。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组产品，输出一个该组的最大收益值。
</p>
<p>
每个结果占一行。
</p>
<h3>
【样例输入】
</h3>
<p>
4  50 2  10 1   20 2   30 1
</p>
<p>
7  20 1   2 1   10 3  100 2   8 2  5 20  50 10
</p>
<h3>
【样例输出】
</h3>
<p>
80
</p>
<p>
185
</p>
<h3>
【测试数据范围】
</h3>
<p>
$0\leq N \leq 10000$
</p>
<p>
$1\leq p_i,d_i \leq 10000$
</p>
<h3>
【来源】
</h3>
<p>
<a href="https://www.acwing.com/problem/content/147/">AcWing 145 超市</a> 
</p>
