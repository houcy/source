# 题目描述


<div><b>【问题描述</b>】</div>
<div>大家会不会觉得多项式运算是一个很复杂的问题呢?<br/>
现在给出多项式的手写形式(如x+1，3x^3-2x^2+2)，要求进行各种运算。<br/>
运算一共有4种，分别为evaluate(代入)，add(加)，subtract(减)，multiply(乘)。</div>
<div><b>【</b>输入格式】</div>
<div><br/>
每个输入数据都有多个运算，行末行首均没有多余空格。所有的字母都是小写，每行都用回车分开。表达式可能出现的字符有0～9，+，-，^，x 任何+，-运算符都不会连续出现两个。下面是几种基本运算的输入格式。<br/>
代入，求出当x等于指定值的时候对应的多项式的值：<br/>
加法，求出所有的多项式的和(输入-1表示运算结束)：<br/>
减法，求出第一个多项式减去后面所有多项式的值(输入-1表示减法结束)：<br/>
乘法，求出所有的多项式的积(输入-1表示乘法结束)：<br/>
若干行多项式<br/>
-1<br/>
结束，表示程序的结束<br/>
last</div>
<div><b>【</b>输出格式】</div>
<div><br/>
输出每种运算以后的结果。首先输出运算的序号，然后紧跟一个冒号，接着是一个空格，最后是运算结果。每种运算的结果占用一行。多项式按降序排列，并且要进行同类项合并。</div>
<div><b>【</b>输入输出样例】<br/>
输入(ploy.in)<br/>
add<br/>
x+1<br/>
2x^2+1<br/>
3x+4<br/>
-1<br/>
evaluate</div>
<div>3<br/>
7x^3+2x^2-10<br/>
last</div>
<div>输出(ploy.out)<br/>
1:2x^2+4x+6<br/>
2:197</div>
<div><b>【</b>数据规模】</div>
<div style1="">多顶式项数&lt;=500 指数&lt;=10^9</div>
