# 

 
 # 题目描述 
<p>
对Samuel星球的探险已经取得了非常巨大的成就，于是科学家们将目光投向了Samuel星球所在的星系——一个巨大的由千百万星球构成的Samuel星系。

 
 # 输入格式 
<p>
第一行有两个整数N，M。表示有N个星球（1< N < 30000），初始时已经有M条航线（1 < M < 100000）。随后有M行，每行有两个不相同的整数A、B表示在星球A与B之间存在一条航线。接下来每行有三个整数C、A、B。C为1表示询问当前星球A和星球B之间有多少条关键航线；C为0表示在星球A和星球B之间的航线被破坏，当后面再遇到C为1的情况时，表示询问航线被破坏后，关键路径的情况，且航线破坏后不可恢复； C为-1表示输入文件结束，这时该行没有A,B的值。被破坏的航线数目与询问的次数总和不超过40000。

 
 # 输出格式 
<p>
对每个C为1的询问，输出一行一个整数表示关键航线数目。
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5 5
1 2
1 3
3 4
4 5
4 2
1 1 5
0 4 2
1 5 1
-1

</td><td>1
3