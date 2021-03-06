# 题目描述


<p>
	有N头奶牛(1 &lt;= N &lt;= 100,000)，共有K个不同的技能 (1 &lt;= K &lt;= 30).
</p>
<p>
	FJ给每个奶牛一个整数ID, ID可以展开成K-bit的二进制数。比如某头奶牛的ID = 13.  则二进制数1101, 那么表示该奶牛有三个技能，分别是：1、 3、4 (从右往左读)。
</p>
<p>
	FJ 把1..N头奶排在一条直线上，然后惊喜的发现，某一段连续的奶牛是“平衡的”。
所谓的平衡是指：这K个技能中的任何一种技能在该连续奶牛段中出现的次数相同。
FJ想知道：最长“平衡的”奶牛连续段有多长。
</p>
<h3>
	输入格式
</h3>
<ul>
	<li>
		第 1行: 两个整数： N 、 K.
	</li>
	<li>
		第 2..N+1行: 每行一个整数，第 i+1行的整数表示第i头奶牛的ID.
	</li>
</ul>
<h3>
	样例输入(balline.in)
</h3>
<pre>7 3
7
6
7
2
1
4
2</pre>
<h3>
	样例解释
</h3>
有7头奶牛，有3 种技能。如下表所示：
<pre>技能 3:      1   1   1   0   0   1   0
技能 2:      1   1   1   1   0   0   1
技能 1:      1   0   1   0   1   0   0
ID:          7   6   7   2   1   4   2
Cow #:       1   2   3   4   5   6   7</pre>
<h3>
	输出格式
</h3>
<ul>
	<li>
		第1行:一个整数. 最长“平衡的”奶牛连续段有多长。
	</li>
</ul>
<h3>
	样例输出 (balline.out)
</h3>
<pre>4</pre>
<h3>
	输出解释
</h3>
从奶牛3 到奶牛6（共4头）,每种技能都有两头奶牛具备:
<pre>技能 3:     1   0   0   1  -&gt; two total
技能 2:     1   1   0   0  -&gt; two total
技能 1:     1   0   1   0  -&gt; two total
ID:         7   2   1   4 
Cow #:      3   4   5   6 </pre>
