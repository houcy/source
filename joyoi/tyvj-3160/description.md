# 

 
 # 题目描述 
<p>
第三幕 生死攸关的咒语<br> <br>　　"吱呀呀"厚重的大门打开了,居然没有那种腐朽的气味,难道因为这里是神殿吗?劳拉有些疑惑不解，"管不了那么多了，还是赶快找到水晶头骨要紧。"她环顾四周，这里虽然很宽敞，却一目了然，空旷的大厅只有一张桌子，上面有许多刻有数字的石板。水晶头骨会在哪儿呢？劳拉走到桌子前，刚想看个究竟，突然，三面墙向她压了过来，同时，一个缥缈的声音在神殿里响起："每个石板上的数字串都是一个咒语元素，用这些咒语元素连接成一条咒语，就可以阻止墙的移动。咒语是由咒语元素连接而成的数字串，且每条咒语至少能用2种不同的连接方法得到，不同的连接顺序可以看成是不同的方法，祝你好运。"<br>　　在这生死攸关的时刻，劳拉亟需你的帮助，因为时间紧迫，所以她希望你能找出长度最短的咒语。桌子上的石板很多，你可以认为每一种石板都有无数多个。<br>任务：<br>　　你必须提供一个名为cantrip.exe的可执行文件，求出长度最短的咒语。 <br></p> 

 
 # 输入格式 
<p>
　　输入文件第一行有一个整数n(2<=n<=200)，以下n行每行为一个长度不超过100的数字串，即n种不同的石板上刻的数字串。</p> 

 
 # 输出格式 
<p>
　　第一行是一个整数，代表你所找到的长度最短的咒语的长度。第二行是你找到的咒语，若有多种拼法使咒语长度最短，则输出按照字典排序最小的一个。数据保证有解。</p> 
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
<tr><td>　　4
　　11
　　111
　　00
　　000
</td><td>　　5
　　00000</td></tr></table>
