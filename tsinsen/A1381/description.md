<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont"><b>【问题描述】</b><br/>
　　在平面直角坐标系中，Wayne需要你完成n次操作，操作只有两种：<br/>
　　1.0  x y。表示在坐标系中加入一个以(x, y)为圆心且过原点的圆。<br/>
　　2.1 x y。表示询问点(x, y)是否在所有已加入的圆的内部（含圆周），且至少在一个圆内部（含圆周）。<br/>
　　为了减少你的工作量，题目保证圆心严格在x轴上方（纵坐标为正），且横坐标非零。<br/>
<b></b><br/>
<b>【输入格式】</b><br/>
　　第1行一个整数n。<br/>
　　接下来n行，每行第一个数是0或1，分别表示两种操作。<br/>
　　接着有两个实数x和y，具体意义见题面。<br/>
<b></b><br/>
<b>【输出格式】</b><br/>
　　对于每个询问操作，如果点在所有已加入的圆内（或圆周上），则输出“Yes”（不含引号）；否则输出“No”（不含引号）。</div>
# 样例输入

<div class="pddata">5<br/>
0 2.0000 3.0000<br/>
0 4.0000 1.0000<br/>
1 1.000000 1.000000<br/>
0 -3.0000 2.0000<br/>
1 1.000000 1.000000</div>
# 样例输出

<div class="pddata">Yes<br/>
No</div>
# 样例说明

<div class="pdcont">　　<img src="source/tsinsen/A1381/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9N0FlTXk5eWc=.do" width="400" height="283"/>`<br/>
<br/>
<br/>
　　如图，第一次询问时圆D并未加入，E在圆B和圆C内；第二次询问时E不在圆D内。<br/>
<br/>
<b>【数据规模】</b><br/>
　　对于30%的数据，n≤1000；<br/>
　　对于40%的数据，输入数据可看作是不相关的随机数；<br/>
　　对于另外20%的数据，n≤100000，圆的交区域不会由多于20条圆弧组成；<br/>
　　对于另外20%的数据，第一次出现查询操作后不再加圆；<br/>
　　对于100%的数据，n≤500000，所有坐标绝对值不超过10000。<br/>
　　输入数据保证圆心纵坐标为正，横坐标非零。<br/>
　　圆心坐标保留4位小数，询问点坐标保留6位小数，请选手注意控制精度。</div>

</div>