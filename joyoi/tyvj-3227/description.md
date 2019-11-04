# 

 
 # 题目描述 
<p>
球星（football.pas/c/cpp）

 
 # 输入格式 
<p>
　　第一行包括一个整数N(1≤N≤50000)，表示运动员的总数。紧跟着的N行，每行描述一位球员。0≤年份≤1000000000，名字的长度少于15个字母，0≤能力≤1000000000。输入保证没有两个名字是一样。然后一行有一个整数R，表示询问数(1≤R≤100000)。紧跟着的R行，每行包含两个整数x和y(0≤x≤y≤1000000000)，表示查询的时期的年份范围为[x,y]。</p> 

 
 # 输出格式 
<p>
　　对于每个询问，输出11个球员的名字，按球员的ability从高到低排序，如果一样，按年份从低到高排序，如果还是一样，按姓名的字典序排序。如果查询的年份范围内的球员数少于11，则剩下的每行都输出”XXX”。在每个询问后输出一个空行。</p> 

 
 # 提示 
<p>
对于所有数据，1≤N≤50000, 0≤年份≤1000000000, 0≤能力≤1000000000。1≤R≤100000，每个询问中0≤x≤y≤1000000000。</p> 
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
1 a 1
2 b 2
2 c 6
5 e 50
5 d 50
2
1 2
5 5
</td><td>c
b
a
XXX
XXX
XXX
XXX
XXX
XXX
XXX
XXX

d
e
XXX
XXX
XXX
XXX
XXX
XXX
XXX
XXX
XXX