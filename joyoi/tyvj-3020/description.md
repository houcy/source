# 

 
 # 题目描述 
<p>
Bill在研究学校里的蚂蚁，他饲养了许多蚂蚁，分为若干蚁群。

 
 # 输入格式 
<p>
输入文件的第一行包含一个整数N(1≤N≤100)，表示有N个蚁群和N棵苹果树。接下来N行描述N个蚁群的聚居地，再接着N行描述N棵苹果树。每个蚁群和苹果树都由一对整数x和y描述（-10000 ≤ x, y ≤10000）。所有点都在同一平面上。所有蚁群和苹果树占据平面上的不同点。不会出现三点共线的情况。</p> 

 
 # 输出格式 
<p>
输出N行，每行一个整数。第i行上写的数字表示第i个（1到N）蚁群连向的苹果树的编号。</p> 
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
<tr><td>5
-42 58
44 86
7 28
99 34
-13 -59
-47 -44
86 74
68 -75
-68 60
99 -60
</td><td>4
2
1
5
3