# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;大家都知道胖子是一名机械工程师，他很胖，然而最近遇到了一件烦心事，这件事是如此的烦心，以至于他的体重锐减20%！<br>&nbsp;&nbsp;&nbsp;&nbsp;烦心事来自一位设计师瘦子给胖子的机器3D设计图纸，瘦子是如此的没有力气，以至于将图纸画得模糊不清，而且这个方形机器中居然没有除工件外的空位，胖子800度的视力受到严重考验，于是他终日食之不得下咽。<br>&nbsp;&nbsp;&nbsp;&nbsp;胖子终于无法忍受，决定求助于最新科技——电脑，他买来一台联想电脑（带闪联），借助它进行图纸辨别，但是电脑上没有这样的软件，于是胖子以1斤肉作为奖励，希望你帮他设计一个软件。 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;胖子说：“我的图纸是三维的（先进吧），用坐标系分了网格，每个工件包含相邻的一些网格部分，由于万恶的瘦子很愚蠢，我不得不认为模糊程度相差在一定范围的相邻两格是同一工件，你就帮我看看总共有多少个工件吧”。 

 
 # 输入格式 
第一行3个整数l,w,h&nbsp;(l,w,h&lt;=50)&nbsp;表示三维图纸的长宽高；<br>第二行1个整数m(0&lt;=m&lt;=255)表示模糊程度的最大允许差值；<br>后面有一行l*w*h个0~255的非负整数，按照空间坐标从小到大给出瘦子画每一格的模糊程度(坐标大小比较，按长，宽，高的优先顺序)。 

 
 # 输出格式 
一个整数，工件个数。 
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
<tr><td>2 2 2
0
1 1 1 1 2 2 2 2</td><td>2</td></tr></table>
