# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
BlackJack（又名21点）起源于法国，是一种简单易懂的双人赌博游戏，于19世纪的欧美风靡一时，现已流传到了世界各地。
</p>
<p>
BlackJack使用若干副去掉大小王的扑克牌来完成游戏，每副牌中A~K各四张。在游戏中，A~K分别被标记为A,2,3,4,5,6,7,8,9,T,J,Q,K。其中，2~9这8张牌所代表的点数分别为2~9本身；T,J,Q,K所代表的点数都为10；A的点数由持有这张A的玩家在清算时自己任意规定为1或11。显然，持有这张A的玩家一定会按照对自己有利的原则来规定它代表的数值。特别地，如果一方玩家持有两张A，这两张A所代表的数值不一定相同。
</p>
<p>
根据BlackJack的规则，两个人每人等概率随机抽取两张牌来比较手牌点数和。如果两方的手牌点数和都大于21点，判为平局；如果只有一方手牌点数和大于21点，判另一方赢；如果双方手牌点数和都不大于21点，判点数较大的一方赢，若手牌点数相同，判为平局。
</p>
<p>
你来到了Las Vegas的赌场，准备和一位庄家小赌一场，你知道这次赌局使用了n副去掉了大小王的扑克牌。你和庄家各自随机抽取了两张手牌，其中庄家有一张手牌是“明牌”——即你可以看到你自己的两张手牌和庄家的明牌，庄家只能看到他自己的两张手牌。现在，到了你下注的时候了——显然，你需要计算一下自己能赢庄家的概率。
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
第一行一个整数n，表示赌局使用了多少副去掉了大小王的扑克牌。
</p>
<p>
接下来一行用空格隔开的三个字符，分别代表庄家的“明牌”和你自己的两张手牌。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个实数，表示你能够赢庄家的概率，保留五位小数。
</p>
<h3>
【样例输入1】
</h3>
<pre><p>
1
</p>

<p>
T A J
</p>

<p>
<br/>

</p>

<p>
样例2：
</p>

<p>
<br/>

</p>

<p>
4
</p>

<p>
2 3 4
</p>

<p>
<br/>

</p>
</pre>
<h3>
【样例输出1】
</h3>
<pre>0.93878</pre>
<pre><p>
样例2：0.21951
</p>
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
对于第1组样例，庄家的另一张手牌有52-3=49种可能性。根据对自己有利的原则，你将你手中的A规定为11点，你的手牌点数和是21。显然只有庄家的另一张手牌是A的时候，你和庄家才会打成平手，否则你一定能赢。而庄家的另一张手牌是A只有3种可能性，所以，你赢庄家的概率=(49-3)/49= 0.93878.
</p>
<p>
对于第2组样例，你的手牌点数和是7，庄家的另一张手牌是4或者比4小（除了A以外，因为如果庄家有A一定会把A规定为11点）的时候，你才能赢庄家。而庄家的另一张手牌有52*4-3=205种可能性，是2或3或4的情况有3*4*4-3 =45种可能性。因此，你赢庄家的概率=45/205=0.21951.
</p>
<p>
<br/>
</p>
<p>
对于30%的数据，1&lt;=n&lt;=20。
</p>
<p>
对于100%的数据，1&lt;=n&lt;=1000，输入的三个字符都在A,2,3,4,5,6,7,8,9,T,J,Q,K这13个字符的范围内。
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
Freda Rodriguez Shi提供题目
