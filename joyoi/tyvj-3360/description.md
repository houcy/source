# 

 
 # 题目描述 
<p>
社交网站（fejs.pas\c\cpp） <br><br>【问题描述】<br>　　社交网站现在已经成为人们生活中不可或缺的一部分。一个有趣的现象就是朋友的数量在飞速增长。俗话说“我朋友的朋友是我的朋友”，每个人都会检查他朋友的朋友列表，并把其中的新朋友加进自己的朋友列表。建立一段新的友情需要一天时间。所以，如果A和B准备确认建立一段友情，A在这一天之后才会在朋友列表中看到B。<br>　　朋友关系是对称的——如果A是B的朋友，那么B也是A的朋友。<br>　　因为在这道题目中，友情是不能破裂的，所以在某一个时刻，有可能任何人之间都建立了友情。<br>　　写一个程序，计算出要使得所有人之间都建立起朋友关系所需要的天数，并计算出每天会有多少对新朋友诞生。<br></p> 

 
 # 输入格式 
<p>
　　输入文件fejs.in包括两个整数N和M(1 ≤ N ≤ 50, 1 ≤ M ≤ N × (N - 1) / 2)，表示人数和初始的朋友数。<br>　　接下来M行，每行两个整数A和B(1 ≤ A ≤ N, 1 ≤ B ≤ N, A < B)，表示A和B是朋友。数据保证一定存在解。<br></p> 

 
 # 输出格式 
<p>
　　输出文件fejs.out的第一行的数K表示多少天后所有人才会互相成为朋友。<br>　　接下来K行，每行输出一个数，表示这一天有多少对新朋友诞生。<br></p> 
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
<tr><td>【输入样例1】
3 2
1 2
2 3

【输入样例2】
5 4
1 2
2 3
3 4
4 5

【输入样例3】
5 4
1 2
1 3
1 4
1 5

</td><td>【输出样例1】
1
1

【输出样例2】
2
3
3

【输出样例3】
1
6</td></tr></table>
