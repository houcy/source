# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
春天静悄悄地来了。HJ站在窗前，欣赏着这和谐的万物。他背着手，慢步踱行，吟诵道：“春色满园关不住，一枝红杏出墙来”，好诗啊！（HJ不愧是有知识的人）。正当HJ沉醉在这美妙的世界中时，邪恶的大爷突然出现了，他要破坏这充满爱的人间。HJ义不容辞地阻止大爷的邪恶计划。大爷给HJ下了一个挑战题：
</p>
<p>
  HJ得到了一个有n个数的A序列（互不相同）：a1,a2,a3……an。
</p>
<p>
  若每个数是这个序列中第bi小的，由此我们可以得到一个新的B序列：b1,b2,b3…..bn。
</p>
<p>
  由于大爷排列组合非常厉害，所以他要求HJ将这个B序列往后按字典序生成10个排列。
</p>
<p>
  例：
</p>
<p>
A序列：120 205 529 206 671
</p>
<p>
B序列：1 2 4 3 5
</p>
<p>
往后生成的10个排列：
</p>
<p>
1th: 1 2 4 5 3
</p>
<p>
2th: 1 2 5 3 4
</p>
<p>
3th: 1 2 5 4 3
</p>
<p>
4th: 1 3 2 4 5
</p>
<p>
5th: 1 3 2 5 4
</p>
<p>
6th: 1 3 4 2 5
</p>
<p>
7th: 1 3 4 5 2
</p>
<p>
8th: 1 3 5 2 4
</p>
<p>
9th: 1 3 5 4 2
</p>
<p>
10th: 1 4 2 3 5
</p>
<p>
因为HJ要去交大搞ACM了，所以他把这个任务交给了你。战胜大爷，拯救世界吧！
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
输入文件包含2行：
</p>
<p>
   第1行是整数n，表示A序列的长度。
</p>
<p>
第2行共n个数，表示a1,a2,a3…..an（每两个数之间有一个空格）。
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
输出文件包含10行:
</p>
<p>
第i行:   total_i:_B序列后第i个排列(数与数之间要有空格)
</p>
<p>
每个序列后都要有一个空行（包括最后一行）
</p>
<p>
如果大爷失误了：可能B之后没有10个排列，那么就有几个排列输出几个排列。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5
</p>

<p>
120 205 529 206 671
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
total 1: 1 2 4 5 3
</p>

<p>
<br/>

</p>

<p>
total 2: 1 2 5 3 4
</p>

<p>
<br/>

</p>

<p>
total 3: 1 2 5 4 3
</p>

<p>
<br/>

</p>

<p>
total 4: 1 3 2 4 5
</p>

<p>
<br/>

</p>

<p>
total 5: 1 3 2 5 4
</p>

<p>
<br/>

</p>

<p>
total 6: 1 3 4 2 5
</p>

<p>
<br/>

</p>

<p>
total 7: 1 3 4 5 2
</p>

<p>
<br/>

</p>

<p>
total 8: 1 3 5 2 4
</p>

<p>
<br/>

</p>

<p>
total 9: 1 3 5 4 2
</p>

<p>
<br/>

</p>

<p>
total 10: 1 4 2 3 5
</p>

<p>
<br/>

</p>
</pre>
<h3>
【提示】
</h3>
<p>
请仔细阅读输出格式
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2016
</p>
