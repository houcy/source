# 

 
 # 题目描述 
<p>
【问题背景】<br>小K攒足了路费来到了教主所在的宫殿门前，但是当小K要进去的时候，却发现了要与教主守护者进行一个特殊的游戏，只有取到了最大值才能进去Orz教主……<br><br>【问题描述】<br>守护者拿出被划分为n个格子的一个圆环，每个格子上都有一个正整数，并且定义两个格子的距离为两个格子之间的格子数的最小值。环的圆心处固定了一个指针，一开始指向了圆环上的某一个格子，你可以取下指针所指的那个格子里的数以及与这个格子距离小于k的格子的数，取一个数的代价即这个数的值。指针是可以转动的，每次转动可以将指针由一个格子转向其相邻的格子，且代价为圆环上还剩下的数的最大值。<br>现在对于给定的圆环和k，求将所有数取完所有数的最小代价。<br></p> 

 
 # 输入格式 
<p>
输入文件cirque.in的第1行有两个正整数n和k，描述了圆环上的格子数与取数的范围。<br>第2行有n个正整数，按顺时针方向描述了圆环上每个格子上的数，且指针一开始指向了第1个数字所在的格子。<br>所有整数之间用一个空格隔开，且不超过10000。<br></p> 

 
 # 输出格式 
<p>
输出文件cirque.out仅包括1个整数，为取完所有数的最小代价。</p> 

 
 # 提示 
<p>
<br><img src="/source/joyoi/tyvj-2886/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg4Ni9wcm9ibGVtc19pbWFnZXMvMzQ0OC9wZy5qcGc=.jpg"></img><br>【数据规模】<br>对于20%的数据，n≤10，k≤3；<br>对于40%的数据，n≤100，k≤10；<br>对于60%的数据，n≤500，k≤20；<br>对于100%的数据，n≤2000，k≤500。<br></p> 
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
<tr><td>6 1
4 1 2 3 1 3
</td><td>21</td></tr></table>
