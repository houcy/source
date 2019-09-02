# 题目描述


<dt>
问题描述
</dt>
<dd>
<p>
世博会志愿者的选拔工作正在 A 市如火如荼的进行。为了选拔最合适的人才，A 市对所有报名的选手进行了笔试，笔试分数达到面试分数线的选手方可进入面试。面试分数线根据计划录取人数的150%划定，即如果计划录取m名志愿者，则<b>面试分数线为排名第m*150%（向下取整）名的选手的分数</b>，而最终进入面试的选手为笔试成绩不低于面试分数线的所有选手。
</p>
<p>
<br/>
</p>
现在就请你编写程序划定面试分数线，并输出所有进入面试的选手的报名号和笔试成绩。
<p>
<br/>
</p>
</dd>
<dt>
输入
</dt>
<dd>
<p>
第一行，两个整数n，m（5 ≤ n ≤ 5000，3 ≤ m ≤ n），中间用一个空格隔开，其
中n 表示报名参加笔试的选手总数，m 表示计划录取的志愿者人数。输入数据保证m*150%
向下取整后小于等于n。
第二行到第 n+1 行，每行包括两个整数，中间用一个空格隔开，分别是选手的报名号k
（1000 ≤ k ≤ 9999）和该选手的笔试成绩s（1 ≤ s ≤ 100）。数据保证选手的报名号各
不相同。
</p>
</dd>
<dt>
输出
</dt>
<dd>
<p>
第一行，有两个整数，用一个空格隔开，第一个整数表示面试分数线；第二个整数为
进入面试的选手的实际人数。
从第二行开始，每行包含两个整数，中间用一个空格隔开，分别表示进入面试的选手
的报名号和笔试成绩，按照笔试成绩从高到低输出，如果成绩相同，则按报名号由小到大的
顺序输出。
</p>
</dd>
<dt>
输入输出样例
</dt>
<dd>
<table>
<thead>
<tr>
<th>
score.in
</th>
<th>
score.out
</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<pre>6 3
1000 90
3239 88
2390 95
7231 84
1005 95
1001 88</pre>
</td>
<td>
<pre>88 5
1005 95
2390 95
1000 90
1001 88
3239 88</pre>
</td>
</tr>
</tbody>
</table>
<p>
m*150% = 3*150% = 4.5，向下取整后为4。保证4 个人进入面试的分数线为88，但因为88有重分，所以所有成绩大于等于88 的选手都可以进入面试，故最终有5 个人进入面试。
</p>
</dd>