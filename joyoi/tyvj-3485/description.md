# 

 
 # 题目描述 
<p>
有一个球形空间产生器能够在n维空间中产生一个坚硬的球体。现在，你被困在了这个n维球体中，你只知道球面上n+1个点的坐标，你需要以最快的速度确定这个n维球体的球心坐标，以便于摧毁这个球形空间产生器。

 
 # 输入格式 
<p>
第一行是一个整数，n。

 
 # 输出格式 
<p>
有且只有一行，依次给出球心的n维坐标（n个实数），两个实数之间用一个空格隔开。每个实数精确到小数点后3位。数据保证有解。你的答案必须和标准输出一模一样才能够得分。
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
0.0 0.0
-1.0 1.0
1.0 0.0
</td><td>0.500 1.500

数据规模：
对于40%的数据，1<=n<=3
对于100%的数据，1<=n<=10
提示：给出两个定义：
1、	球心：到球面上任意一点距离都相等的点。
2、	距离：设两个n为空间上的点A, B的坐标为(a1, a2, …, an), (b1, b2, …, bn)，则AB的距离定义为：dist = sqrt( (a1-b1)^2 + (a2-b2)^2 + … + (an-bn)^2 )