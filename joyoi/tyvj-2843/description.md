# 

 
 # 题目描述 
<p>
根据外星人的回信，在遗迹中有分布着三样道具。当三样道具都拿走后，遗迹就很快自动毁灭，所以必须要在最短时间内离开。遗迹可以看作是由N个房间(编号1..N)和N-1条长度不等通道所组成，并且任意两个房间之间有且只有一条路可以相互到达。现在我们的队员已经在编号为A,B,C的房间内拿到道具，并且准备撤退。由于只有一架直升机，所以只能在一个房间上停留。现在请你决定将直升机停在哪一个房间之上，能够使三人到达该房间的距离之和最短。</p> 

 
 # 输入格式 
<p>
第1行：四个整数N A B C

 
 # 输出格式 
<p>
第1行：一个整数，表示汇合房间的编号。若存在多个解，输出字典序最小的。

 
 # 提示 
<p>
[数据范围]
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
<tr><td>5 3 1 4
3 5 5
4 3 9
4 1 7
1 2 1
</td><td>4
16