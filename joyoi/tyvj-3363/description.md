# 

 
 # 题目描述 
<p>
城市位置（karta.pas\c\cpp） <br><br>【问题描述】<br>　　一个地区的地图由R行S列的方格组成。<br>　　在地图上标记了一些城市。城市的位置用'x'标记，而城市的名字用一些大写字母从左到右表示。对于每一个城市，它的名字都靠近它所在的位置。更确切的说，名字中至少存在一个字母在城市所在位置的邻近的8个位置中的一个。<br>　　在地图中，有些城市会比较靠近，并且可能出现在某些城市周围的8个格子中有多个名字。但是存在且只存在一种方案使它们一一配对。<br>　　写一个程序确定所有城市的位置，以及与它们配对的名字。<br></p> 

 
 # 输入格式 
<p>
　　输入文件karta.in的第一行包含两个数R和S (1 ≤ R ≤ 50, 1 ≤ S ≤ 50)，表示地图的行数和列数。<br>　　接下来的R行，包含了地图的具体内容。每一个字符都是'.'、小写字母'x'或者大写英文字母。<br>　　输入数据保证只存在一个城市与名字一一对应的方案，并且没有两个在同一行的名字会首尾相连。<br></p> 

 
 # 输出格式 
<p>
　　输出文件karta.out对于每一个城市，输出一行表示这个城市在地图中的行和列以及它的名字。行从上到下从1到R编号，列从左到右从1到S编号。城市可以以任意顺序输出。</p> 
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
<tr><td>【输入样例1】
12 31
...............................
.............ZAGREB............
..............x................
.......................OSIJEKx.
.....x.........................
......RIJEKA...................
...............................
...............................
...............................
..............SPLIT............
...............x...............
...............................


【输入样例2】
3 8
.VELIKI.
x.....x.
..MALI..
</td><td>【输出样例1】
3 15 ZAGREB
4 30 OSIJEK
5 6 RIJEKA
11 16 SPLIT

【输出样例2】
2 1 VELIKI
2 7 MALI</td></tr></table>
