# 

 
 # 题目描述 
<p>
　　某一村庄在一条路线上安装了n盏路灯，每盏灯的功率有大有小（即同一段时间内消耗的电量有多有少）。老张就住在这条路中间某一路灯旁，他有一项工作就是每天早上天亮时一盏一盏地关掉这些路灯。

 
 # 输入格式 
<p>
 　　文件第一行是两个数字n(0 < n < 50，表示路灯的总数)和c(1 <＝ c <= n老张所处位置的路灯号)；

 
 # 输出格式 
<p>
　　一个数据，即最少的功耗(单位：J，1J＝1W&#8226;s)。</p> 

 
 # 提示 
<p>
【算法分析】
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
<tr><td>5 3					
2 10
3 20
5 20
6 30
8 10
</td><td>270 　　　{此时关灯顺序为3 4 2 1 5，不必输出这个关灯顺序}</td></tr></table>