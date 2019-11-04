# 

 
 # 题目描述 
<p>
Windy有N个不同重量的小球，重量分别为1到N个单位。现在他想按如下方法给小球编号为1到N： 

 
 # 输入格式 
<p>
输入的第一行代表测试数据的组数。每组测试数据第一行包含两个整数N (1 ≤ N ≤ 200) 和 M (0 ≤ M ≤ 40,000)。接下来的M行每一行包含两个整数a 和 b 表示编号为a的小球必须必编号为b的小球更轻。(1 ≤ a, b ≤ N) 每组测试数据前面有一行空行。 </p> 

 
 # 输出格式 
<p>
对于每组测试数据，输出单独一行表示编号1到N的小球的重量。如果有多种方案，输出的方案必须使最小重量编号为1，最小重量编号为2，最小重量编号为3，等等……如果不存在解决方案，输出-1。</p> 
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
<tr><td>5

4 0

4 1
1 1

4 2
1 2
2 1

4 1
2 1

4 1
3 2
</td><td>1 2 3 4
-1
-1
2 1 3 4
1 3 2 4