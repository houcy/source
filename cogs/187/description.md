# 题目描述


<p>
农夫约翰有一个老式的打谷机（收麦子用）需要把皮带安置在不同的齿轮上以转动零件，发动机驱动皮带轮轮1顺时针方向转着，通过一个皮带，带动轮2。轮2带动论3......总计有n（1&lt;=n&lt;=1000）个轮子（和n-1个皮带）。
</p>
<p>
<a href="/wiki/Image:Belts1.jpg"><img border="0" alt="Image:Belts1.jpg" src="/mw/images/6/69/Belts1.jpg" width="284" height="274"/></a> 
</p>
<p>
上面的插图描绘了两种把皮带安置在轮上的方法。如图所示，轮1的皮带直接驱动轮2（“直接的”连接）所以它们有相同的转动方向。轮3用一个“交叉的”皮带连接轮4，所以它们有不同的方向。
</p>
<p>
我们将给出所有皮带的安置方式，以及每个皮带系统中的驱动轮和从动轮。未给出的事实是轮1被发动机以顺时针方式驱动，请求出轮n的转动方向。每个皮带用3个整数描述：
</p>
<ul>
<li>
S_i--驱动轮
</li>
<li>
D_i--从动轮
</li>
<li>
C_i--方向类型（0=直接的，1=交叉的）
</li>
</ul>
<p>
不幸的是，农夫约翰将以随机的顺序给出轮的信息。
</p>
<p>
用来做例子，请考虑下面的插图。n=4，轮1是被发动机顺时针驱动的，直接的皮带连接轮1和轮2，轮2和轮3，交叉的皮带连接轮3和轮4。所以轮4（轮n）是逆时针方向。
</p>
<p>
<a href="/wiki/Image:Belts2.jpg"><img border="0" alt="Image:Belts2.jpg" src="/mw/images/3/3a/Belts2.jpg" width="635" height="273"/></a> 
</p>
<p>
分数：70
</p>
<p>
题目名称：rotation
</p>
<p>
输入格式：
</p>
<ul>
<li>
第一行：一个单独的整数N
</li>
<li>
第2..n行：S_i,D_i,C_I
</li>
</ul>
<p>
输入样例（file ratation.in）：
</p>
<pre>4
2 3 0
3 4 1
1 2 0
</pre>
<p>
输出格式：
</p>
<p>
第一行：一个整数，表示轮n的转动类型。
</p>
<p>
输出样例（file rotation.out）：
</p>
<pre>1
</pre>
