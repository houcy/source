# 

 
 # 题目背景 
外星人完成对S国的考察后，准备返回，可他们的飞碟已经没燃料了……<BR>S国的专家暗自窃喜……复仇的机会终于来了——他们打算敲诈外星人一大笔钱……<BR> 

 
 # 题目描述 
S国有n个燃料基地，保存有外星人所需的全部燃料，编号分别为1,2,3,…,n，对于每个燃料基地i，都有【((i-1)&nbsp;mod&nbsp;10)+1】吨燃料。其中，编号&lt;=5的燃料基地两两之间都有可双向通行的路；对于其余每个燃料基地i，与(i-1),(i-3)之间，也有可双向通行的路。对于任意两燃料基地i,j，若之间有路将他们【直接】连接，则通过这条路的运费为【(i*j)mod10+(i+j)mod6+1)】(单位：元/吨)。<BR>S国的专家要按每吨一元的价格把燃料卖给外星人，并且要它们支付运费。那么，外星人应选择把所有燃料运往那个燃料基地，才能尽可能的让S国专家失望？它们所要支付的最小费用是多少？<BR>注：数据保证解的唯一性。 

 
 # 输入格式 
仅有一个整数n。<BR> 

 
 # 输出格式 
第一行：外星人所要支付的最小费用；<BR>第二行：可供外星人选择的燃料基地的编号。<BR> 

 
 # 提示 
样例解释：<BR>第1-5个基地两两间有路，第6个基地与第3,5个基地间有路。当把全部燃料运到第五个基地时，总费用最少，为107.<BR><BR>数据范围：<BR>对于&nbsp;30%的数据，有5&lt;N&lt;50;<BR>对于&nbsp;60%的数据，有5&lt;N&lt;500;<BR>对于100%的数据，有5&lt;=N&lt;700;<BR>输出数据范围请大家自行判断。<BR><BR> 
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
<tr><td>6
</td><td>107
5
</td></tr></table>
