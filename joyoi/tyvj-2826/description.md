# 

 
 # 题目描述 
<p>
Kamir很喜欢吃软糖。但经过精密计算，Kamir发现在下一个发薪日之前，她平均一天只能吃两颗软糖。于是她郁闷了……她去超市买了一大包软糖，然后准备平均分配到每一天。她把软糖分成了两排，然后每天吃掉排头的那两颗。<br>但是，她发现了一个很严重的问题：她并不满意吃软糖的序列，因为这个序列无法使她获得最大的享受。<br>乐于助人的你当然愿意帮她重新构造一个新的序列，来让Kamir获得最大的享受吧！<br>Kamir已经给每一颗软糖都打好了分，她某一天的享受值即这一天吃的两颗软糖的分数的乘积。你需要构造一个序列，使满意度最大。<br>并且，为了不刺激Kamir的自尊心，希望你交换尽量少的软糖就达到这个序列。同时，因为Kamir对第一排很满意，你只能在第二排的软糖之间交换。<br></p> 

 
 # 输入格式 
<p>
第一行为一个整数n，表示有n天。<br>第二行n个正整数，表示第一排软糖的分数。<br>第三行n个正整数，表示第二排软糖的分数。<br><br></p> 

 
 # 输出格式 
<p>
一个整数，表示最少的交换次数。</p> 

 
 # 提示 
<p>
数据范围：<br>对于30%的数据，1<=n<=10<br>对于100％的数据，1<=n<=100，000（难怪Kamir郁闷……），分数<=maxlongint,保证同一排的软糖分数不同。<br> <br></p> 
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
<tr><td>2
1 2
2 1
</td><td>1</td></tr></table>
