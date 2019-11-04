# 

 
 # 题目描述 
<p>
成都的驾驶考试在一个有n条平行的自南向北的单向的道路的场地中进行。每条道路长度为m米，并且都在同一条水平线上开始和结束。街道从西向东分别编号为1到n。同样有p条单向的自西向东或自东向西的街道垂直于上面描述的街道，每一条这样的街道链接了两个相邻的自南向北的道路。当然自西向东和自东向西的道路可以重叠，那就是一个双向的街道了。

 
 # 输入格式 
<p>
输入第一行包含四个整数n,m,p和k(2<=n<=100000， 1<=m,k<=100000， 0<=p<=100000)。分别表示南北向的道路数，南北向道路的长度，东西向的道路数和最多能够添加的道路数。

 
 # 输出格式 
<p>
输出中仅包含一个整数，最大的能够作为起点的道路数。注意添加的道路不能与南北向的道路相交，并且到起始水平线的距离为整数。添加的道路可以重叠，表示双向的道路。
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
<tr><td>4 3 5 2
2 0 0
2 2 1
3 3 1
1 1 1
3 3 0
<img border="0" src="/source/joyoi/tyvj-3563/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU2My9wcm9ibGVtc19pbWFnZXMvMjQwNi8xMTA3XzIuanBn.jpg">



</td><td>
2
</td></tr></table>