# 

 
 # 题目描述 
<p>
静音问题

 
 # 输入格式 
<p>
第一行有三个整数n，m，c（ 1<= n<=1000000，1<=m<=10000， 0<=c<=10000），分别表示总的采样数、静音的长度和静音中允许的最大噪音程度。第2行n个整数ai (0 <= ai  <= 1,000,000)，表示声音的每个采样值，每两个整数之间用空格隔开。

 
 # 输出格式 
<p>
列出了所有静音的起始位置i（i满足max(a[i, . . . , i+m&#8722;1]) &#8722; min(a[i, . . . , i+m&#8722;1]) <= c），每行表示一段静音的起始位置，按照出现的先后顺序输出。如果没有静音则输出NONE。
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
<tr><td>7 2 0
0 1 1 2 3 2 2
</td><td>2
6