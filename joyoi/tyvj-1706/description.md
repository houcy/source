# 

 
 # 题目背景 
幻影国建成了当今世界上最先进的高铁，该国高铁分为以下几类：<BR>S---高速光子动力列车---时速1000km/h<BR>G---高速动车---时速500km/h<BR>D---动车组---时速300km/h<BR>T---特快---时速200km/h<BR>K---快速---时速150km/h<BR>该国列车车次标号由上述字母开头，后面跟着一个正整数(&lt;=1000)构成。 

 
 # 题目描述 
由于该国地形起伏不平，各地铁路的适宜运行速度不同。因此该国的每一条行车路线都由K列车次构成。例如：K=5的一条路线为：T120-D135-S1-G12-K856。当某一条路线的末尾车次与另一条路线的开头车次相同时，这两条路线可以连接起来变为一条更长的行车路线。显然若干条路线连接起来有可能构成一个环。<BR><BR>若有3条行车路线分别为:<BR>x1-x2-x3<BR>x3-x4<BR>x4-x5-x1<BR>x1~x5车次的速度分别为v1~v5<BR>定义高铁环的值为(环上各条行车路线速度和)的平均值，即：<BR>[(v1+v2+v3)+(v3+v4)+(v4+v5+v1)]/3.<BR>所有高铁环的值的最大值称为最优高铁环的值。<BR>给出M条行车路线，求最优高铁环的值。 

 
 # 输入格式 
第一行为行车路线条数M<BR>接下来M行每行一条行车路线，由若干车次构成，各车次之间用'-'号隔开，车次的标号方式如上所述。<BR>数据保证输入的合法性。<BR> 

 
 # 输出格式 
最优高铁环的值。四舍五入到最接近的整数。<BR>若不存在这样的环，输出-1. 

 
 # 提示 
样例解释：<BR>[(200+300+1000)+(1000+500)+(500+150+200)]/3=1283<BR><BR>数据范围：<BR>50%的数据：0&lt;M&lt;=1000<BR>100%的数据，0&lt;M&lt;=50000<BR>每条行车路线车次个数不超过20.<BR><BR>输入数据较大，请使用read和scanf。数据不保证使用cin者不超时。<BR>为避免精度问题，请使用double类型。<BR>数据保证结果不超过2147483647.LYD 
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
<tr><td>3
T120-D135-S1
S1-G12
G12-K856-T120
</td><td>1283
</td></tr></table>