# 

 
 # 题目描述 
届时，牧草将被有顺序的分成了&nbsp;n&nbsp;组，m只奶牛于是排好队伍，按顺序等待talent先生发放若干组牧草给自己，按照规则，奶牛们得到的牧草的分组编号一定是连续的，由于每组牧草的草量并非都一样，每只奶牛得到的牧草组数也未必一样，所以，这必将会造成一定程度上的不公平，talent先生希望尽量维护这种公平，于是他想到了一个方法--------让得到牧草最多的那只奶牛的牧草尽可能的少。<BR><BR>举个例子，假如牧草有5组，奶牛有两只。。。<BR>每组牧草的草量分别为：1,2,3,4,5<BR>于是，最佳的分配方案就是（1，2，3）（4，5）<BR>这样，得到最多牧草的奶牛拥有的牧草是4+5=9,<BR>是我们所期待的最小的值。<BR><BR><BR> 

 
 # 输入格式 
第一行，2个整数，n,m<BR>第二行，n个整数，表示每组牧草的含草量 

 
 # 输出格式 
一个整数，即：最佳分配方案下，拥有草最多的那只奶牛的有草量<BR> 

 
 # 提示 
对于20%的数据，k&lt;=n&lt;=50<BR>对于40%的数据，k&lt;=n&lt;=1000<BR>对于60%的数据，k&lt;=n&lt;=100000<BR>对于100%的数据，n不超过2000000 
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
<tr><td>5 2
1 2 3 4 5
</td><td>9
</td></tr></table>
