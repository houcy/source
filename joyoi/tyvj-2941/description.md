# 

 
 # 题目描述 
<p>
这是一个很难的问题，你要找出“12345678987654321！”答案里一共含有多少个“0”，“！”表示阶乘的意思。

 
 # 输入格式 
<p>
	数据第一行是两个整数N和M，(1<=N<=200，0<=M<=10000)，分别表示交叉路口数量与通路数量。接下来M行每行有三个整数i，j，k（i!=j，1<=k<=10000），表示有一条长度为k的无向通路连接路口i与路口j。注意路口i与路口j间可能有多条不同长度的通路。

 
 # 输出格式 
<p>
	输出只有一个整数，为最短的逃离距离，如果不可能逃出，则输出“-1”。
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
<tr><td>2 1
1 2 3
</td><td>3