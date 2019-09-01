<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　一个序列a[0],a[1],a[2]..被称为重复序列，如果a[]中的每一项都是0或1，并且存在系数序列c[1],c[2],..c[k]使得c[1]..c[k]均为0或1，而且a[n]=(c[1]*a[n-1]+c[2]*a[n-2]+..+c[k]*a[n-k]) mod 2 对于每一项n&gt;=k的a[n]成立。假设序列a和c中的元素并不全为0。<br/>
　　显然给定系数序列c[]和a[]的前k项之后，我们就可以得到n&gt;=k的每一个a[n]。由于(a[0],a[1],..,a[k-1])这一k元组只有(2^k)-1种可能，并且由这一k元组可以唯一确定接下来的一项，所以这一序列的循环节至多是(2^k)-1。<br/>
　　如果一个重复序列a[]的最小循环节恰为(2^k)-1，我们称之为长序列。给定k，请输出一个长序列a[]中的前k项，以及对应的系数序列c[1..k]。</div>
# 输入格式

<div class="pdcont">　　一行一个整数K.</div>
# 输出格式

<div class="pdcont">　　如果不存在这样的长序列，输出&#34;-1&#34;（不含引号）。<br/>
　　否则输出两行，第一行为c[1],c[2]..c[k]，第二行为a[0],a[1]..a[k-1]。<br/>
　　如果存在多组解，请输出其中的任意一组。</div>
# 样例输入

<div class="pddata">3</div>
# 样例输出

<div class="pddata">0 1 1<br/>
1 1 1</div>
# 数据规模和约定

<div class="pdcont">　　2&lt;=K&lt;=50.</div>

</div>