<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont"><b>【问题描述】</b><b></b><br/>
　　给一个正整数n，输出它所有的正整数加法的分解方法。<br/>
　　注意：<br/>
　　1．           根据输入的要求决定交换加数的位置是否视为不同的分解方案。<br/>
　　2．           不分解也视为一种分解方案。<br/>
　　3．           按字典序输出所有分解方案，格式见样例。<br/>
<br/>
<b>【输入格式】</b><b></b><br/>
　　输入共1行，包含2个正整数n和m，之间用一个空格隔开。n表示待分解正整数，m是1或者2：<br/>
　　1表示交换加数的位置是否视为<b>不同</b>的分解方案；<br/>
　　2表示交换加数的位置是否视为<b>相同</b>的分解方案。<br/>
<b>【输出格式】</b><b></b><br/>
　　输出若干行，每行表示一种分解方案。对于一种方案，先输出n，再输出一个“=”。然后输出分解的各数，不同的数之间用一个“+”连接。</div>
# 样例输入

<div class="pddata">5 2</div>
# 样例输出

<div class="pddata">5=1+1+1+1+1<br/>
5=1+1+1+2<br/>
5=1+1+3<br/>
5=1+2+2<br/>
5=1+4<br/>
5=2+3<br/>
5=5<br/>
<br/>
<br/>
<b>【输入输出样例2】</b></div>
# 样例输入

<div class="pddata">5 1</div>
# 样例输出

<div class="pddata">5=1+1+1+1+1<br/>
5=1+1+1+2<br/>
5=1+1+2+1<br/>
5=1+1+3<br/>
5=1+2+1+1<br/>
5=1+2+2<br/>
5=1+3+1<br/>
5=1+4<br/>
5=2+1+1+1<br/>
5=2+1+2<br/>
5=2+2+1<br/>
5=2+3<br/>
5=3+1+1<br/>
5=3+2<br/>
5=4+1<br/>
5=5</div>
# 数据规模和约定

<div class="pdcont">　　对于50%的数据有M=1，另有50%的数据有M=2。对100%的数据，n≤15。</div>

</div>