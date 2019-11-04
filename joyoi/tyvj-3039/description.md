# 

 
 # 题目描述 
<p>
某列精灵列车途经C个城市，城市编号依次为1到C。列车上共有S个座位，精灵王规定售出的车票只能是坐票，换言之保证搭乘该列车的所有旅客都有座位。售票系统是由计算机执行的，每一个售票申请包含三个参数，分别用O、D、N表示，O为起始站，D为目的地站，N为车票张数。售票系统对该售票申请做出受理或不受理的决定，只有在从O到D的区段内列车上都有N个或N个以上的空座位时该售票申请才被受理。请你写一个程序，实现这个自动售票系统。</p> 

 
 # 输入格式 
<p>
第1行：包含三个用空格隔开的整数C、S和R，其中1≤C≤60000， l≤S≤60000，1≤R≤60000。C为城市个数，S为列车上的座位数，R为所有售票申请总数。

 
 # 输出格式 
<p>
第1…R行：每行输出一个“YES”或“NO”，表示当前的售票申请被受理或不被受理。</p> 
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
<tr><td>4 6 4
l 4 2
l 3 2
2 4 3
l 2 3
</td><td>YES
YES
NO
NO