# 

 
 # 题目描述 
国防部计划用无线网络连接若干个边防哨所。2种不同的通讯技术用来搭建无线网络；每个边防哨所都要配备无线电收发器；有一些哨所还可以增配卫星电话。<BR>任意两个配备了一条卫星电话线路的哨所均可以通话，无论它们相距多远。而只通过无线电收发器通话的哨所之间的距离不能超过D，这是受收发器的功率限制。收发器的功率越高，通话距离D会更远，但同时价格也更贵。<BR>收发器需要统一购买和安装，所以全部哨所只能选择安装一种型号的收发器。换句话说，每一对哨所之间的通话距离都是同一个D。<BR>你的任务是确定收发器必须的最小通话距离D，使得每一对哨所之间至少有一条通话路径（直接的或者间接的）。<BR> 

 
 # 输入格式 
第1行：2个整数S（1≤S≤100）和P（S﹤P≤500），S表示可安装的卫星电话的线路数，P表示边防哨所的数量。<BR>接下来P行，每行描述一个哨所的平面坐标（x，y），以km为单位，整数，0≤x，<BR>y≤10，000.<BR> 

 
 # 输出格式 
第1行：1个实数D，表示无线电收发器的最小传输距离。精确到小数点后两位。 
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
<tr><td>2 4
0 100
0 300
0 600
150 750
</td><td>212.13</td></tr></table>
