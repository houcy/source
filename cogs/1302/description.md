# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
假设有n根柱子，现要按下述规则在这n根柱子中依次放入编号为 1，2，3，4......的球。
</p>
<p>
（1）每次只能在某根柱子的最上面放球。
</p>
<p>
（2）在同一根柱子中，任何2个相邻球的编号之和为完全平方数。
</p>
<p>
试设计一个算法，计算出在n根柱子上最多能放多少个球。例如，在4 根柱子上最多可
</p>
<p>
放11个球。
</p>
<p>
编程任务：
</p>
<p>
对于给定的n，计算在 n根柱子上最多能放多少个球，并输出方案。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
文件共1行，即1个正整数n，表示柱子数。
</p>
<h3>
【输出格式】
</h3>
<p>
文件共n+1行：
</p>
<p>
第1行是最多的球数S；
</p>
<p>
第2至n+1行有Mi+1个整数，每行是一根柱子上的球的编号。
</p>
<h3>
【样例输入】
</h3>
<pre>4</pre>
<h3>
【样例输出】
</h3>
<pre><p>
11
</p>

<p>
1 8
</p>

<p>
2 7 9
</p>

<p>
3 6 10
</p>

<p>
4 5 11
</p>
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
数据规模：
</p>
<p>
n&lt;=60  保证答案小于1600
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
【网络流24题】
</p>
<p>
<a href="/cogs/problem/problem.php?pid=396" target="_blank">本题简化版</a> 
</p>
