# 

 
 # 题目描述 
<p>
拦截匪徒问题（catch.pas/c/cpp）

 
 # 输入格式 
<p>
　　输入文件catch.in第一行为N，P（1<=P<=N<=200)

 
 # 输出格式 
<p>
　　输出文件catch.out输出N-1行，按顺序从j=1,2,…p-1,p+1,…,n依次输出对于每一个j，警察可以在哪些点埋伏。有多个点的话，要按从小到大顺序依次输出。没有的话那一行输出NO。
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
<tr><td>5 1
0 1 1 0 0
1 0 1 1 0
1 1 0 0 0
0 1 0 0 1
0 0 0 1 0
</td><td>NO
NO
2
2 4