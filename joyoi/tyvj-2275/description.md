# 

 
 # 题目描述 
<p>
这里有 N 座城镇, 和城镇之间的 M 巴士单行线(没有中间停靠站)。 城镇从1到N 标号。 一个旅行者在 0时刻位于 1号城镇想要到达 P 号城镇。他将乘坐巴士在T 时刻到达P 号城镇。如果他早到了，他必须等待。

 
 # 输入格式 
<p>
The first line contains the integer numbers N (1<=N<=50,000), M (1<=M<=100,000), P ( 1<= P<= N), and T (0<=T<=1,000,000,000).

 
 # 输出格式 
<p>
只需要包含一个数——最合理搭车方案的最长可能等待时间。如果不可能保证在T 时刻到达城市P，那么输出-1。

 
 # 提示 
<p>
The most pessimistic case for the optimal travel plan for the above example is as follows:
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
<tr><td>3 6 2 100
1 3 10 20 30 40
3 2 32 35 95 95
1 1 1 1 7 8
1 3 8 8 9 9
2 2 98 98 99 99
1 2 0 0 99 101
</td><td>32</td></tr></table>