# 

 
 # 题目描述 
<p>
在二维网格平面上有许多机器人在移动。每个机器人的状态由它所在的位置和面向的方位确定。每个机器人按照各自固定的指令执行移动。位置由一对整数(x, y)表示。机器人的方向有4个，用角度表示，分别是0，90，180，270。命令有两种，转身和移动。转身命令有一个参数D，是90，180或270，机器人当前的方向改变D个度数，C度将变为(C&nbsp;+&nbsp;D)&nbsp;mod&nbsp;360。移动指令没有参数，机器人将按它的方向前进一个单位。0方向的移动，位置改变（1，0），方向90改变（0，1），方向180改变（-1，0），方向270改变（0，-1）。

 
 # 输入格式 
<p>
Input data should be read from the file robots.in. The first line of the file contains 

 
 # 输出格式 
<p>
需要去掉的最少的命令数

 
 # 提示 
<p>
There are 2 moving robots. The first robot has initial position (2, 0), direction 270 and a 
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
2 0 270 5 
S 
T 180 
S 
S 
S 
1 -1 0 8 
S 
S 
T 90 
S 
T 270 
S 
T 90 
S </td><td>2</td></tr></table>