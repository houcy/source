# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
LongDD 将军为了平息延续数年战乱，决定释放战俘营中所有的俘虏。然而，LongDD将军不打算释放敌军的统帅LongMM——因为这个家伙异常聪明，是个难缠的对手。所以LongDD将军决定把LongMM用链子固定到墙上。链子由n个环组成，每个环有可能在墙上，也可能不在墙上。
</p>
<p>
“LongDD将军，你为什么把我绑在墙上，不让我获得自由”，LongMM咆哮道。
</p>
<p>
“但是，LongMM，你并没有被绑在墙上。我很确定你可以自己把链子解开”，LongDD将军回答道，“但是请你在天黑之前解开，否则我会因为你制造噪音把你重新抓起来。”
</p>
<p>
请帮助LongMM吧！链子由n个环组成，编号为1,2,…,n。我们可以把每个环从墙上取下来或者从新放回墙上，但是需要遵循如下规则：
</p>
<p>
-  每一步只能取下或者装上一个环
</p>
<p>
-  编号为1的环可以随意取下或装上
</p>
<p>
-  如果编号为1,…,k-1的环都取下了，并且编号为k的环在墙上，我们可以随意取下或者装上第k+1个环
</p>
<p>
-  当所有环都取下来之后，LongMM可以逃脱了
</p>
<p>
给定每个环的初始状态，请你编写程序计算LongMM最少需要多少步才能逃脱。
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
* 第 1 行: 有一个整数n，(1&lt;=n&lt;=1000)，表示环的个数
</p>
<p>
* 第 2 行: 有n个整数，第i个整数为0表示第i个环在初始的时候为摘下的状态；如果为1 ，表示第i个环初始的时候为装在墙上的状态。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
* 第 1 行: 只有一个整数，表示最少需要多少步才能让LongMM逃脱。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
4
</p>

<p>
1 0 1 0<span style="font-family:monospace;"></span> 
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>6</pre>
<h3>
【提示】
</h3>
<p>
高精度
</p>
<h3>
【来源】
</h3>
<p>
并不知道
</p>
