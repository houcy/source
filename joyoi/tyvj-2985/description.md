# 

 
 # 题目描述 
<p>
很多人都曾经听说过数独，但你是否听说过数谜（Karuro）呢？实际上，数谜是数独的更大（且更难）的兄弟问题，而且在日本也是非常受欢迎的。

 
 # 输入格式 
<p>
输入包含多组测试数据。第一行包含一个正整数T，表示测试数据数目。每组数据第一行是n(n<10)和m(m<10)，表示数谜的形状的大小。接下来一行有n个整数，是相应的行要求；然后一行是m个整数，是相应的列要求。接下来的n行每行有m个小于10的非负整数，0表示该空格还没有被填数字，其他表示coolzzz同学已经填好的数字。输入数据保证未填数字的空格不会超过16个。</p> 

 
 # 输出格式 
<p>
对于每组测试数据，输出若干行。如果基于coolzzz已填的结果，该数谜只有一个解，则输出该解；如果不止一个解，则输出一行“Not unique.”；如果没有解，则输出一行“No answer.”。
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
<tr><td>3
3 3
6 6 6
6 6 6
0 0 0
0 3 0
0 0 0
2 3
10 17
5 16 6
2 0 0
0 9 0
2 2
3 5
4 4
0 0
0 0
</td><td>Not unique.
2 7 1
3 9 5
No answer.