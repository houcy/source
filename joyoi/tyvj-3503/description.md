# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-3503/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzUwMy9wcm9ibGVtc19pbWFnZXMvMjMzMy8yLmpwZw==.jpg">

 
 # 输入格式 
<p>
输入的第一行为一个整数n，表示每支代表队的人数。

 
 # 输出格式 
<p>
包括两个用空格隔开的整数，分别表示浙江队在最好与最坏的情况下分别能得多少分。不要在行末输出多余的空白字符。
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
<tr><td>2
1
3
2
4
</td><td>
2 0
样例说明
我们分别称4位选手为A,B,C,D。则可能出现以下4种对战方式，最好情况下可得2分，最坏情况下得0分。
	一	二	三	四
	浙江	???	结果	浙江	???	结果	浙江	???	结果	浙江	???	结果
一号选手	A	C	负	A	D	负	B	C	胜	B	D	负
二号选手	B	D	负	B	C	胜	A	D	负	A	C	负
总得分	0	2	2	0

</td></tr></table>