# 题目描述


<h3>
【题目描述】
<p></p>
</h3>
      九连环是由九个彼此套接的圆环和一根横杆组成,九个环从左到右依次为1-9,每个环有两种状态:1和0,1表示环在杆上,0表示环不在杆上.初始状态是九个环都在杆上,即:111111111,目标状态是九个环都不在环上,即:000000000,由初始状态到目标状态的变化规则是:
<p>
&lt;1&gt;第一环为无论何时均可自由上下横行.
</p>
<p>
&lt;2&gt;第二只环只有在第一环为1时,才能自由上下.
</p>
<p>
&lt;3&gt;想要改变第n(n&gt;2)个环的状态,需要先使第一到第(n-2)环均为下杆,且第n-1个环为上杆,而与第N+1个到第九环状态无关.
</p>
<p>
&lt;4&gt;每改变一个环,记为一步.
</p>
<p>
现在九连环由111111111变到000000000,求中间第I步的状态。
</p><p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
仅包含一个整数i,表示第i步的距离。
</p>
<h3>
【输出格式】
</h3>
<p>
输出中间第i步的状态，如果输入的步数大于实际变换所需的步数，输出-1。
</p>
<h3>
【样例输入1】
</h3>
<pre>2</pre>
<h3>
【样例输出1】
</h3>
<pre>010111111</pre>
<p>
<br/>
</p>
<h3>
【样例输入2】
</h3>
<pre>500</pre>
<h3>
【样例输出2】
</h3>
<pre>-1
</pre>
<h3>
【提示】
</h3>
<pre>1&lt;=i&lt;=2^31-1</pre>
