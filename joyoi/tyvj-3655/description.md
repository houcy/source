# 

 
 # 题目描述 
<p>
写一个程序来模拟操作系统的进程调度。假设该系统只有一个CPU，每一个进程的到达时间，执行时间和运行优先级都是已知的。其中运行优先级用自然数表示，数字越大，则优先级越高。

 
 # 输入格式 
<p>
输入文件包含若干行，每一行有四个自然数（均不超过108），分别是进程号，到达时间，执行时间和优先级。不同进程有不同的编号，不会有两个相同优先级的进程同时到达。输入数据已经按到达时间从小到大排序。输入数据保证在任何时候，等待队列中的进程不超过15000个。</p> 

 
 # 输出格式 
<p>
按照进程结束的时间输出每个进程的进程号和结束时间</p> 
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
<tr><td>1 1 5 3
2 10 5 1
3 12 7 2
4 20 2 3
5 21 9 4
6 22 2 4
7 23 5 2
8 24 2 4</td><td>
1 6
3 19
5 30
6 32
8 34
4 35
7 40
2 42</td></tr></table>