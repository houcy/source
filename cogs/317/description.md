# 题目描述


<p>
[题目描述]
</p>
<p>
某人有一套玩具，并想法给玩具命名。首先他选择WING四个字母中的任意一个字母作为玩具的基本名字。然后他会根据自己的喜好，将名字中任意一个字母用“WING”中任意两个字母代替，使得自己的名字能够扩充得很长。
</p>
<p>
现在，他想请你猜猜某一个很长的名字，最初可能是由哪几个字母变形过来的。
</p>
<p>
[输入]
</p>
<ul>
<li>
第一行四个整数W、I、N、G。表示每一个字母能由几种两个字母所替代。
</li>
<li>
接下来W行，每行两个字母,表示W可以用这两个字母替代。
</li>
<li>
接下来I行，每行两个字母,表示I可以用这两个字母替代。
</li>
<li>
接下来N行，每行两个字母,表示N可以用这两个字母替代。
</li>
<li>
接下来G行，每行两个字母,表示G可以用这两个字母替代。
</li>
<li>
最后一行一个长度不超过Len的字符串。表示这个玩具的名字。
</li>
</ul>
<p>
[输出]
</p>
<ul>
<li>
一行字符串，该名字可能由哪些字母变形而得到。（按照WING的顺序输出）
</li>
<li>
如果给的名字不能由任何一个字母变形而得到则输出“The name is wrong!”
</li>
</ul>
<p>
[样例]
</p>
<p>
Input
</p>
<pre>1 1 1 1
II
WW
WW
IG
IIII
</pre>
<p>
Output
</p>
<pre>IN
</pre>
<p>
[样例解释]
</p>
<ul>
<li>
W可以变成II所以IIII可以缩成WW
</li>
<li>
IN均能变成WW所以WW又可以缩成I或者N
</li>
<li>
所以最终答案应该按照“WING”的顺序输出IN
</li>
</ul>
<p>
[数据范围]
</p>
<ul>
<li>
30%数据满足Len&lt;=20，W、I、N、G&lt;=6
</li>
<li>
100%数据满足Len&lt;=200，W、I、N、G&lt;=16
</li>
</ul>
