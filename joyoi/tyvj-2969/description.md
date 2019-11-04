# 

 
 # 题目描述 
<p>
最近科学家们在研究一个很庞大的原子核家族——“X家族”。他们发现这个家族中的所有原子核都非常相似，只能通过质量来区分它们。质量相差越小，它们之间相互转化的可能性就越大。

 
 # 输入格式 
<p>
输入第一行是一个整数N（1 <= N <= 100000），表示总共有多少条操作指令。

 
 # 输出格式 
<p>
对于每一条query指令，输出一行，包含一个整数，即当前最小的质量差或者-1。</p> 

 
 # 提示 
<p>
对于30%的数据，N <= 100。</p> 
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
<tr><td>12
generate 1
remove 2
generate 1
query
generate 7
query
generate 10
query
generate 5
query
remove 7
query
</td><td>-1
6
3
2
4