
# Content

“来！炸个痛快！”--` Ziggs`

最近，方老师买了个新英雄炸弹人吉格斯。凭着犀利的操作，方老师用炸弹人在国服电信一区打排位，最终冲上了最强王者！吉格斯的技能中，方老师用的最溜的莫过于W技能定点爆破：吉格斯扔出一个炸药包，会在4秒后爆炸，或者在再次施放该技能后爆炸。爆炸会对敌人造成魔法伤害，并将他们击退。吉格斯也会被击退，但不会受到伤害。于是，方老师发明了一个游戏。在一个n×m的棋盘，方老师会指定在一些格子内放置吉格斯的定时炸弹，并由两个人来轮流选择去引爆他们。不过为了增加游戏的趣味性，方老师决定在一个炸弹引爆时，会产生新的炸弹。具体规则是：对于在$(x,y)$处的炸弹，
  1. 如果$x>1$ && $y>1$,那么在引爆这个炸弹时，会在$(a,y)$和$(x,b)$两个位置产生两个新的炸弹$(a<x,b<y)$;
  2. 如果$x=1$ && $y>1$,那么在引爆这个炸弹时，会在$(x,b)$位置产生一个新的炸弹$(b<y)$;
  3. 如果$x>1$ && $y=1$,那么在引爆这个炸弹时，会在$(a,y)$位置产生一个新的炸弹$(a<x)$;

其中炸弹产生的位置，由引爆这颗炸弹的人来选择。此外，还规定如果两个炸弹落在同一格，那么它们将自动引爆；如果炸弹落在$(1,1)$也会自动引爆。最终，谁没有炸弹可以引爆便输了游戏。

方老师制造了一个分身来陪他玩，当然每局游戏都是有方老师为先手。给你一个游戏棋盘，那么请你判断下谁会获胜。假设方老师和他的分身都足够聪明。

# Standard Input

本题有多组输入数据。第一行包含一个正整数$T$表示测试数据组数。每一组数据的第一行包含两个整数$n$和$m$表示棋盘的大小。接下来的$n$行每行有$m$个字符(`.`或`#`)，其中‘.’表示该处为空格，`#`表示该处有炸弹。$(0<n, m \leq 50)$

# Standard Output

对于每组测试数据，输出仅一行。如果方老师本人能够获胜，输出`YES`；否则，输出`NO`。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2
1 1
#
5 5
#...#
..#..
##...
.#.#.
#.#.#</td><td>NO
YES</td></tr></table>


# Constraints



# Note

规定棋盘左上角方格的坐标为$(1,1)$

# Source

