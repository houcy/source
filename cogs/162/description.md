# 题目描述


<p>
译 : zqzas
</p>
<p>
<br/>
FJ带着他的奶牛去看焰火表演.但是他们只能在那里呆一会儿,不能看全部表演.所以Bessie想知道她能在多少个时刻看到焰火. 这次表演有C (1 ≤ C ≤ 100) 个礼炮,每个礼炮每隔Ti (1 ≤ Ti ≤ N)个时刻(所有时刻均为整数)发射一次烟花.所有礼炮在 0 时刻发射第一次,而每个烟花仅能在刚刚被发射的那一个时刻被看到.Bessie将从时刻1到时刻N (1 ≤ N ≤ 2,000,000)观看烟花(包括时刻1和时刻N).
</p>
<p>
帮助Bessie计算她能有多少个时刻看到烟花.
</p>
<p>
<br/>
输入格式:
</p>
<ul>
<li>
第1行:两个用空格隔开的整数 C,N.
</li>
<li>
第2行至第C+1行,每行一个整数Ti.
</li>
</ul>
<p>
输出格式:
</p>
<ul>
<li>
一个整数,表示Bessie能在多少个时刻看到烟花.
</li>
</ul>
<p>
样例输入
</p>
<pre>2 20
4
6
</pre>
<p>
样例输出
</p>
<pre>7
</pre>
<p>
样例说明:
</p>
<pre>   CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCC
2                                   2                                   2 ...
1           1     2     1           1           1     2     1           1 ...
+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+ ...
0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 ...
</pre>
<p>
Bessie从第1时刻到第20时刻看焰火表演. 有2个礼炮发射焰火,第一个每隔4个时刻发射一次;第二个每隔6时刻发射一次.
</p>
<p>
由上图所示,Bessie可以在第4, 6, 8, 12, 16, 18,20时刻看到焰火,共7个时刻. 如果某时刻有多个礼炮同时发射,那么只算1次.
</p>