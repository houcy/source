# 

 
 # 题目描述 
设r是个2^k&nbsp;进制数，并满足以下条件：<BR>（1）r至少是个2位的2^k&nbsp;进制数。<BR>（2）作为2^k进制数，除最后一位外，r的每一位严格小于它右边相邻的那一位。<BR>（3）将r转换为2进制数q后，则q的总位数不超过w。<BR>在这里，正整数k（1≤k≤9）和w（k&lt;w≤30000）是事先给定的。<BR>问：满足上述条件的不同的r共有多少个？<BR>我们再从另一角度作些解释：设S是长度为w&nbsp;的01字符串（即字符串S由w个“0”或“1”组成），S对应于上述条件（3）中的q。将S从右起划分为若干个长度为k&nbsp;的段，每段对应一位2k进制的数，如果S至少可分成2段，则S所对应的二进制数又可以转换为上述的2^k&nbsp;进制数r。<BR>例：设k=3，w=7。则r是个八进制数（2^3=8）。由于w=7，长度为7的01字符串按3位一段分，可分为3段（即1，3，3，左边第一段只有一个二进制位），则满足条件的八进制数有：<BR>2位数：高位为1：6个（即12，13，14，15，16，17），高位为2：5个，…，高位为6：1个（即67）。共6+5+…+1=21个。<BR>3位数：高位只能是1，第2位为2：5个（即123，124，125，126，127），第2位为3：4个，…，第2位为6：1个（即167）。共5+4+…+1=15个。<BR>所以，满足要求的r共有36个。<BR> 

 
 # 输入格式 
输入文件只有1行，为两个正整数，用一个空格隔开：<BR>k&nbsp;W<BR> 

 
 # 输出格式 
输出文件为1行，是一个正整数，为所求的计算结果，即满足条件的不同的r的个数（用十进制数表示），要求最高位不得为0，各数字之间不得插入数字以外的其他字符（例如空格、换行符、逗号等）。<BR>（提示：作为结果的正整数可能很大，但不会超过200位）<BR> 

 
 # 提示 
注：因为出数据者失误，某测试点实际答案超过了maxlongint,但是因为标程使用longint所以大家输出答案的时候要将答案转换成longint输出NOIP2006提高组第4题 
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
<tr><td>3 7
</td><td>36
</td></tr></table>
