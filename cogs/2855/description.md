# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
蒟蒻Edt把这个问题交给了你 ———— 一个精通数据结构的大犇，由于是第一题，这个题没那么难。。
</p>
<p>
edt 现在对于题目进行了如下的简化：
</p>
<p>
最开始的数组每个元素都是0
</p>
<p>
给出nn，optopt，modmod，minmin，maxmax，modmod在int范围内
</p>
<p>
操作A，Q
</p>
<p>
A: L,R,X 表示把[L,R]这个区间加上X
</p>
<p>
（数组的从L到R的每个元素都加上X）
</p>
<p>
Q: L,R 表示询问[L,R]这个区间中元素T满足 min&lt;=(T∗i%mod)&lt;=max的 T这样的数的个数（i是数组下标）
</p>
<p>
（元素的值*数组下标%mod在min到max范围内）
</p>
<p>
由于 edt 请来了一位非三次元的仓鼠，他帮你用延后了部分问题，将这些询问打入了混乱时空，你的询问操作不会超过1000次，不幸的是，对于延后的询问操作可能有很多次（小于1e7次），但是保证这些延后的询问操作之后不会再次有修改操作
</p>
<p>
（就是在最后会有很多次询问，但不会进行修改）
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
给出n，opt，mod，min，max表示序列大小，操作次数，取膜，最小值，最大值
</p>
<p>
下面opt行，给出
</p>
<p>
A: L，R，XX表示区间加，保证X在int范围内(&lt;2147483647）
</p>
<p>
Q：L，R表示区间查询满足条件的个数
</p>
<p>
再给出一个FinalFinal值，表示后面有FinalFinal个询问
</p>
<p>
下面FinalFinal行，给出
</p>
<p>
L，R表示询问区间[L,R]表示询问[L,R]之间满足条件的个数
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
每行对于每个Q操作输出Q个数表示每次询问的值，
</p>
<p>
下面FinalFinal行表示FinalFinal个询问的值
</p>
<p>
<br/>
</p>
<pre>输入样例#1：
3 2 4 0 2
A 1 3 5
Q 2 3
5
1 3
2 3
1 1
2 2
3 3

输出样例#1：
1
2
1
1
1
0

输入样例#2：
17 25 4098 310 2622
A 10 16 657212040
A 4 15 229489140
A 1 2 -433239891
A 3 12 532385784
A 10 17 56266644
A 8 10 10038874
A 6 9 13084764
A 4 5 -9206340
Q 2 8
A 2 4 -43223955
A 6 9 31478706
A 2 4 189818310
A 2 8 179421180
A 2 8 40354938
Q 8 14
A 3 6 57229575
A 6 13 132795740
A 2 17 14558022
A 14 15 -552674185
A 5 11 -1104138
Q 2 12
Q 1 14
A 3 9 524902182
A 8 12 114291440
A 3 7 107531442
1
11 12

输出样例#2：
3
6
7
8
2
</pre>
<h3>
【提示】
</h3>
<p>
<img src="http://ww4.sinaimg.cn/large/0060lm7Tly1fkvxd8ty5bj30ld09labf.jpg" alt=""/> 
</p>
<h3>
【来源】
</h3>
<p>
NOIP 模拟赛 by WISCO信息组
</p>
