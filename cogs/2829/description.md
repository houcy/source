# 题目描述


<h3>
【题目描述】
</h3>
<p>
从前有一个序列a[]，对于每个a[i] 都有一个在序列中的优美值，其定义是：序列中最长的
</p>
<p>
一段[l，r], 满足l ≤ i ≤ r，且a[i] 是这一段的中位数（以数值为第一关键字，下标为第二关键
</p>
<p>
字排序，这样的话这一段的长度只有可能是奇数），r-l+1 就是它的优美值。
</p>
<p>
有Q 个询问，每次给出一段区间，求区间优美值的最大值
</p>
<h3>
【输入格式】
</h3>
<p>
第一行输入n 接下来n 个整数，代表ai 接下来Q，代表有Q 个区间接下来Q 行，每行
</p>
<p>
两个整数l, r(l &lt;= r)，表示区间的左右端点
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个区间的询问，输出答案
</p>
<h3>
【样例输入】
</h3>
<pre>8
16 19 7 8 9 11 20 16
8
3 8
1 4
2 3
1 1
5 5
1 2
2 8
7 8
</pre>
<h3>
【样例输出】
</h3>
<pre>7
3
1
3
5
3
7
3
</pre>
<h3>
【数据范围】
</h3>
<p>
对于30% 的数据满足：1 ≤ n;Q ≤ 50
</p>
<p>
对于70% 的数据满足：1 ≤ n;Q ≤ 2000
</p>
<p>
对于100% 的数据满足，1 ≤ n ≤ 2000, 1 ≤ Q ≤ 100000, 1 ≤ ai ≤ 200
</p>
<h3>
【来源】
</h3>
<p>
2017.10.4 qbxt t1
</p>
