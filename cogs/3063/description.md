# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<img alt="" src="/upload/image/20181129/20181129131229_90267.jpg"/> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
字符串形式输入一个多项式函数。
</p>
<h3>
【输出格式】
</h3>
<p>
字符串形式输出该函数的导函数。
</p>
<h3>
【样例输入】
</h3>
<pre>f(x)=15x^2+23x+6</pre>
<h3>
【样例输出】
</h3>
<pre>f&#39;(x)=30x+23</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
注：函数在初中的表示方法，例如一次函数，y=kx+b
</p>
<p>
在高中的表示方法为f(x)=kx+b
</p>
<p>
事实上跟计算机表示函数的方法非常相似
</p>
<p>
数据范围
</p>
<p>
对于前20个数据，多项式每一项的系数和次数-16384&lt;=x，c&lt;=16384，多项式的项数n&lt;=1000
</p>
<p>
对于第21个数据，-32768&lt;=x,c&lt;=32768,n=10000
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
下文是对导数的几何说明，能否看懂不影响做题。
</p>
<p>
------------------------------华丽的分割线-----------------------------
</p>
<p>
导数，即为一个函数在某点的变化率，如图
</p>
<p>
<img alt="" src="/upload/image/20181129/20181129131802_50347.jpg"/> 
</p>
<p>
如图，熟练的同学可能看出来了，对某一点求导的结果就是函数图像在这一点的切线的斜率
</p>
 <img alt="" src="/upload/image/20181129/20181129131819_21722.jpg"/> 
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
把一个函数的取值作为横坐标，把对这些取值对应的函数图像上的点求导的结果作为纵坐标，描点连线后的新函数，称之为该函数的导函数。y=f(x)的导函数为y’=f’(x).
</p>
<p>
f(x)=mx^n函数的导函数为f’(x)=mn^(n-1)，多项式函数的导函数就是对每一项分别求导，最后连起来。
</p>
<p>
常数的导数为零。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
无
</p>
