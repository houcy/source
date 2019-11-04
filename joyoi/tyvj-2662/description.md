# 

 
 # 题目描述 
<p>
小T有一个很大的书柜。这个书柜的构造有些独特，即书柜里的书是从上至下堆放成一列。她用1到n的正整数给每本书都编了号。

 
 # 输入格式 
<p>
第一行有两个数n，m，分别表示书的个数以及命令的条数；第二行为n个正整数：第i个数表示初始时从上至下第i个位置放置的书的编号；第三行到m+2行，每行一条命令。命令有5种形式： 

 
 # 输出格式 
<p>
对于每一条Ask或Query语句你应该输出一行，一个数，代表询问的答案。
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
<tr><td>10 10 
1 3 2 7 5 8 10 4 9 6
Query 3 
Top 5 
Ask 6 
Bottom 3 
Ask 3 
Top 6 
Insert 4 –1 
Query 5 
Query 2 
Ask 2 

</td><td>2
9
9
7
5
3

数据范围
    30%的数据，n,m < = 10000
    100%的数据，n,m < = 80000
 