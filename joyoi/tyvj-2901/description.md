# 

 
 # 题目描述 
<p>
一个工厂所运行的生产线对每个工件有2道工序A和B，每道工序有一定数量的机器可以实现，分别定义为A类机和B类机。<br>对于每个工件，都必须先经工序A处理，再经工序B处理，而每个机器可以独立的，同时的工作，每个机器工作需要的时间不一样。<br>现有N个工件，找出最早的时间让所有工件完成所有工序A和最早时间完成两道工序。</p> 

 
 # 输入格式 
<p>
第一行 N M1 M2 分别为工件数，A类机数量，B类机数量。<br>第二行 M1个整数描述了每个A类机处理任一个工件的时间。<br>第三行 M2个整数描述了每个B类机处理任一个工件的时间。<br></p> 

 
 # 输出格式 
<p>
一行包含两个整数，分别是最早的时间让所有的工件完成工序A作与最早的时间完成两道工序。</p> 

 
 # 提示 
<p>
数据约定<br>    60%    N<=1000   1<=M1,M2<=30  T<=20    Ans<=maxint <br>    100%   N<=100000 1<=M1,M2<=5000 T<=10000 Ans<=maxlongint<br>评分方式<br>本题有部分分，对于每一个测试点，若你仅有第一个输出正确则得40%分数，若你仅有第二个输出正确则得60%分数，若你两个输出均正确则得100%分数，否则不得分。<br></p> 
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
<tr><td>5 2 3
1 1 
1 3 4
</td><td>3 5</td></tr></table>
