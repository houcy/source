# 题目描述


<p>
<b>【问题描述】</b><br/>
    拱猪是一种很有趣的扑克牌游戏。 即使你不知道它的玩法，你也可以由它的计分方式来了解它的趣味性。 假设在此我们仅考虑四个人的拱猪牌局，本题要求你根据下面的计分规则，在牌局结束时计算四位玩家所得分数。
</p>
<ol>
<li>
我们分别以 S 、 H 、 D 及 C 来代表黑桃，红心，方块及梅花，并以数字 1 至 13 来代表 A 、 2 、 … 、 Q 、 K 等牌点，例如︰ H1 为红心 A ， S13 为黑桃 K 。
</li>
<li>
牌局结束时，由各玩家持有的有关计分的牌 ( 计分牌 ) 仅有 S12 ( 猪 ) ，所有红心牌， D11 ( 羊 ) 及 C10 ( 加倍 ) 等 16 张牌。其它牌均弃置不计。若未持有这 16 张牌之任一张则以得零分计算。
</li>
<li>
若持有 C10 的玩家只有该张牌而没有任何其它牌则得 +50 分，若除了 C10 还有其它计分牌，则将其它计分牌所得分数加倍计算。
</li>
<li>
若红心牌不在同一家，则 H1 至 H13 等 13 张牌均以负分计，其数值为 -50 ， -2 ， -3 ， -4 ， -5 ， -6 ， -7 ， -8 ， -9 ， -10 ， -20 ， -30 ， -40 。而且 S12 与 D11 分别以 -100 及 +100 分计算。
</li>
<li>
若红心牌 H1 至 H13 均在同一家，有下列情形︰
<ul>
<li>
所有红心牌以 +200 分计算(13张总共+200分)。
</li>
<li>
若 S12 、 D11 皆在吃下所有红心牌之一家，则此玩家得 +500 分(这15张总共+500分)。
</li>
<li>
而 C10 还是以前面所述原则计算之。
</li>
</ul>
</li>
</ol>
<p>
例一：若各玩家持有计分牌如下： ( 每行代表一玩家所持有之牌 )
</p>
<p>
S12 H3 H5 H13
</p>
<p>
D11 H8 H9
</p>
<p>
C10 H1 H2 H4 H6 H7
</p>
<p>
H10 H11 H12
</p>
<p>
则各家之得分依序为： -148 、 +83 、 -138 及 -60 。
</p>
<p>
例二：若各玩家持有计分牌如下： ( 第四家未持有任何计分牌 )
</p>
<p>
H1 H2 H3 H4 H5 H6 H7 H8 H9 H10 H11 H12 H13
</p>
<p>
S12 C10
</p>
<p>
D11
</p>
<p>
则各家之得分依序为： +200 、 -200 、 +100 及 0 。
</p>
<p>
例三：若有一玩家持有所有 16 张计分牌，则得 +1000 分。其余三家均得零分。
</p>
<p>
【输入格式】 <br/>
     每个输入文件由多组测试数据构成，每组测试数据有四行，每一行第一个数为该玩家所持有计分牌总数，而后列出其所持有之所有计分牌，牌数与各计分牌均以一个以上的空格分开。相邻两组测试数据之间不会有空白行，读到四家持牌数都为 0 表示文件结束。
</p>
<p>
【输出格式】 <br/>
     每一行输出一组测试数据对应的结果，依次输出各家所得分数，共四个整数 ( 含正负号， 0 除外 ) ，相邻两个整数之间以一个空格分开，符号和数字间不可以有空格。每组输出间不需要有空白行。
</p>
<p>
【输入输出样例】<br/>
 <b><br/>
</b>输入： <br/>
heart.in<br/>
4 S12 H3 H5 H13<br/>
3 D11 H8 H9<br/>
6 C10 H1 H2 H4 H6 H7<br/>
3 H10 H11 H12<br/>
13 H1 H2 H3 H4 H5 H6 H7 H8 H9 H10 H11 H12 H13 <br/>
2 S12 C10<br/>
1 D11<br/>
0<br/>
0<br/>
0<br/>
0<br/>
0<br/>
 
</p>
<p>
输出：<br/>
heart.out<br/>
-148 +83 -138 -60<br/>
+200 -200 +100 0<br/>
 
</p>
