# 题目描述


<p>
	问题描述
</p>
<p>
	有这样一块土地，它可以被划分N*M个正方形小块，每块面积是一平方英寸，第i行第j列的小块可以表示成P(i,j)。这块土地高低不平，每一小块地P(i,j)都有自己的高度H(i,j)(单位是英寸)。
</p>
<p>
	一场倾盆大雨后，由于这块地地势高低不同，许多低洼地方都积存了不少降水。假如你已经知道这块土地的详细信息，你能求出它最多能积存多少立方英寸的降水么?
</p>
<p>
	输入格式
</p>
<p>
	输入文件的第一行是两个正整数n和m,1&lt;=n&lt;=100,1&lt;=m&lt;=100,表示土地的尺寸。下面n行，每行m个整数(1..10000);第j行第i个数表示第j行第i列立方体的高。
</p>
<p>
	输出格式
</p>
<p>
	输出文件只有一个数，表示在这个建筑上可以聚合的积水的最大值
</p>
<p>
	输入输出样例
</p>
<p>
	输入
</p>
<pre>3 6
3 3 4 4 4 2
3 1 3 2 1 4
7 3 1 6 4 1
</pre>
<p>
	输出
</p>
<pre>5
</pre>
<p>
	下图是其方案：
</p>
<p>
	<span><img width="193" height="110" alt="Image:Wod.png" src="../../mw/images/7/73/Wod.png"/></span>
</p>