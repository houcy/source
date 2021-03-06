# 题目描述


<h3>
【题目描述】
</h3>
<center>
<img src="/upload/image/20140118/20140118220646_68808.jpg" alt=""/>
</center>
<p>
在一个位图上进行像素混合有时会产生看似随机的图像。但在重复混合有限次后，总能恢复原始图像。这是意料之中的，因为“混合”意味着对位图上的像素执行一个一一对应的映射（或者叫置换）
</p>
<p>
你的程序被要求读入一个正整数n，和一系列的基本混合命令，定义了一个对n*n位图的像素混合序列φ。然后你的程序要计算出最小的数m(m&gt;0)，使n*n位图在执行m次混合序列φ后总能变成原来的图像。
</p>
<p>
例如，若φ是“逆时针旋转90°”，那么m=4.
</p>
<center>
<img src="/upload/image/20140118/20140118221446_63784.jpg" alt=""/>
</center>
<h3>
【输入格式】
</h3>
<p>
输入文件包含不超过10组数据。
</p>
<p>
输入文件的第一行是数据组数，第二行是空行。接下来分别给出了每组数据，两组数据之间有一个空行。
</p>
<p>
每组数据包含2行。
</p>
<p>
第1行是一个偶数n(2&lt;=n&lt;=2^10)，表示位图的大小。我们用(i,j)描述位图上起第i行，左起第j列的像素。其中i,j从0开始。可以看到，左上角像素的坐标是(0,0)。
</p>
<p>
第2行是一个非空的混合命令序列，至多包含32个命令，命令之间由空格分隔。合法的命令是关键字&#34;id&#34;,&#34;rot&#34;,&#34;sym&#34;,&#34;bhsym&#34;,&#34;bvsym&#34;,&#34;div&#34;,&#34;mix&#34;之一，或者是它们中的某个后面加上&#34;-&#34;。每个关键字都描述了一种置换，如果后面加上&#34;-&#34;，那就意味着该置换的逆置换。例如，&#34;rot-&#34;是逆时针旋转90°的逆置换，即顺时针旋转90°。最终，置换序列k1,k2,...,kp表示了总的置换φ=k1*k2*...*kp。例如，“bvsym rot-”对应的φ意味着将图像顺时针旋转90°，并且将图像的下半部分竖直翻转，如下图所示。
</p>
<center>
<img src="/upload/image/20140118/20140118222348_59511.jpg" alt=""/>
</center>
<p>
下面给出了各种关键字所对应的置换。
</p>
<p>
id：不变。
</p>
<p>
rot：逆时针旋转90°。
</p>
<p>
sym：水平翻转。置换后的(i,j)是原来的(i,n-1-j)。
</p>
<p>
bhsym：水平翻转图像的下半部分。置换后的(i,j)当i&gt;=n/2时是原来的(i,n-1-j)，其余情况则是(i,j)。
</p>
<p>
bvsym：竖直翻转图像的下半部分。
</p>
<p>
div：分割。第0,2,4,...,n-2行依次变成第0,1,...,n/2-1行；第1,3,...,n-1行依次变成第n/2,n/2+1,...,n-1行。
</p>
<p>
mix：行混合。将第2k和第2k+1行交错。第2k行的像素依次是原图的(2k,0),(2k+1,0),(2k,1),(2k+1,1),...,(2k,n/2-1,2k+1,n/2-1)。第2k+1行的像素依次是原图的(2k,n/2),(2k+1,n/2),(2k,n/2+1),(2k+1,n/2+1),...,(2k,n-1),(2k+1,n-1)。
</p>
<p>
下图给出了原图分别进行7种置换后的效果。
</p>
<center>
<img src="/upload/image/20140118/20140118223314_37226.jpg" alt=""/>
</center>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出题中要求的m，即使φ^m称为“不变”的最小m。数据保证m&lt;2^31.
</p>
<p>
两组数据的输出之间用一个空行分隔。
</p>
<h3>
【样例输入】
</h3>
<pre>2
256
rot- div rot div
256
bvsym div mix
</pre>
<h3>
【样例输出】
</h3>
<pre>8
63457
</pre>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=485&amp;page=show_problem&amp;problem=3597" target="_blank">UVa 1156 Pixel Shuffle</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2-10
</p>
