<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一个n*m的棋盘，棋盘中每个元素都是字符&#34;L&#34;,&#34;R&#34;,&#34;X&#34;三者之一。<br/>
<br/>
　　每个元素都有一个状态，“活动”或“非活动”。 最初矩阵中每个元素都是“活动”的。<br/>
<br/>
　　Lemon和Melon在这个矩阵上进行回合制博弈，双方轮流进行操作。Lemon先手。<br/>
<br/>
　　每次操作是这样的：<br/>
<br/>
　　轮到操作的人选择一个状态是“活动”的格子。然后根据格子上的字符，将会发生以下3种事件。<br/>
<br/>
　　如果格子上字符是&#34;L&#34;，格子会以自身为起点，向左下方和右上方对角线方向发出2条射线，射线在碰到“非活动”的格子或超出棋盘边界时才会停止。随后，射线经过的格子（包括选择的格子自身）全部变成“非活动”状态。<br/>
<br/>
　　如果格子上字符是&#34;R&#34;，格子会以自身为起点，向右下方和左上方对角线方向发出2条射线，射线效果同上。<br/>
<br/>
　　如果格子上字符是“X”，格子会以自身为起点，向左上、左下、右上、右下对角线方向发出4条射线，射线效果同上。<br/>
<br/>
　　如果轮到某人操作时，所有的格子都是非活动状态的，那么这个人就输了，游戏结束。<br/>
<br/>
　　Lemon想知道对于给定的棋盘，他是否有必胜策略。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个整数n, m，分别表示给定棋盘的行数和列数。接下来n行，每行m个字符，表示给定棋盘。</div>
# 输出格式

<div class="pdcont">　　仅一行。如果Lemon有必胜策略，则输出&#34;WIN&#34;，否则输出&#34;LOSE&#34;</div>
# 样例输入

<pre class="pddata">2 2
RL
LR
【样例输出】
LOSE
【数据规模和约定】
对20%的数据有n,m&lt;=4
</pre>
<div class="pddata">对100%的数据有n,m&lt;=20,  n,m均为正整数.</div>

</div>