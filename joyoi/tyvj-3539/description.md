# 

 
 # 题目描述 
<p>
“余”人国的国王想重新编制他的国家。他想把他的国家划分成若干个省，每个省都由他们王室联邦的一个成员来管理。

 
 # 输入格式 
<p>
第一行包含两个数N，B（1<=N<=1000, 1 <= B <= N）。接下来N－1行，每行描述一条边，包含两个数，即这条边连接的两个城市的编号。

 
 # 输出格式 
<p>
如果无法满足国王的要求，输出0。否则输出数K，表示你给出的划分方案中省的个数，编号为1..K。第二行输出N个数，第I个数表示编号为I的城市属于的省的编号，第三行输出K个数，表示这K个省的省会的城市编号，如果有多种方案，你可以输出任意一种。
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
<tr><td>8 2 
1 2 
2 3 
1 8 
8 7 
8 6 
4 6 
6 5 

</td><td>3 
2 1 1 3 3 3 3 2 
2 1 8 