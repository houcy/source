<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　很久很久以前有一个星系。　　Darth Wader发现了反叛者基地的位置。现在他想用死星摧毁这个基地。　　反叛者发现了这一计划。现在，他们准备用地雷（星雷？）阻止Darth Wader.　　三维空间中布置着N个地雷，每个地雷由球形雷体和若干引线组成。雷体的半径为r，球心为O；每条引线可以被看作连接球心与球外某个点P的线段。方便起见，我们用向量p表示该引线，于是P=O+p。<br/>
　　死星的半径为R，从点A出发匀速运动，其速度可以用向量v表示。在运动过程中，如果它接触到某个地雷的雷体或引线，则它立即被摧毁。其中接触的定义是星球与地雷（雷体或引线）存在公共点。如果在运动过程中星球永远不与任何地雷相交，则它不会被摧毁。<br/>
　　编程计算该星球能否被摧毁。如果它能被摧毁，计算它被摧毁的时间。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含7个整数Ax, Ay, Az, vx, vy, vz, R，依次表示星球的初始位置，速度向量和它的半径。<br/>
　　第二行有一个整数N，表示地雷的个数。<br/>
　　接下来有N块输入，每块描述一个地雷。<br/>
　　第i块的第一行包含5个整数Oix, Oiy, Oiz, r[i], m[i]，依次表示第i个地雷雷体的球心，雷体半径和引线个数。接下来m行，每行三个整数pjx, pjy, pjz，为第j条引线的向量表示。</div>
# 输出格式

<div class="pdcont">　　如果星体能被摧毁，输出一个实数，表示其被摧毁的时间；否则输出&#34;-1&#34;(不含引号)。<br/>
　　输出可以包含任意多位，但是其与答案的误差不能超过10^(-6)。</div>
# 样例输入

<div class="pddata">0 0 0 1 0 0 5<br/>
2<br/>
10 8 0 2 2<br/>
0 -3 0<br/>
2 2 0<br/>
20 0 0 4 3<br/>
2 4 0<br/>
-4 3 0<br/>
1 -5 0</div>
# 样例输出

<div class="pddata">10.000000000</div>
# 数据规模和约定

<div class="pdcont">　　1 &lt;= N &lt;= 100<br/>
　　-10 &lt;= vx, vy, vz &lt;= +10, |v| &gt; 0<br/>
　　0 &lt; R &lt;= 100<br/>
　　对于地雷i，0 &lt; r[i] &lt; R, 0 &lt;= m[i] &lt;= 10; 对于每条引线p, r[i] &lt; |p| &lt; 3r[i] / 2。<br/>
　　对于任意两个地雷i, j, dis(O[i], O[j]) &gt; 3/2 * (r[i] + r[j])。</div>

</div>