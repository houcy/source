# 

 
 # 题目描述 
Assassin's&nbsp;Creed&nbsp;II的主角Ezio接受了一个任务：清除A城的所有卫兵。已知A城有N个路口，M条道路，路口之间被道路连接着（道路没有方向之分，且A城各个路口之间一定是直接或间接连通的），而卫兵们分散在各个道路上巡逻。<BR><BR>因为A城实在很大，Ezio如果单独去执行任务的话，很容易陷入被围攻的境地，所以，Ezio可以雇佣了其他刺客。Ezio可以安排刺客们在某些路口执行任务，刺客们可以清除掉这个与他所在的路口相连道路上的所有敌人。当然，事情不会这么顺利，在每个路口安置刺客上都有不同的风险度。幸运的是，Ezio事先评估了这些路口的风险度，这能大大的提高任务的成功率。<BR><BR>另外，刺客们互相都不一定认识，如果其中的两人被安排到了路口A和路口B，而路口A和B之间又有道路相连，那么，这两个刺客完全有可能会将对方当成敌人，互相残杀。这时Ezio不希望看到的。<BR><BR>所以，Ezio现在唯一的问题就是，找到一种风险度最低的方案，使得A城所有士兵都能被清除，自己人又不被误杀。<BR> 

 
 # 输入格式 
第一行是两个数字N和M，表示A城有N个路口，M条道路。(N&nbsp;&lt;=&nbsp;M&nbsp;&lt;=1000000)<BR>第二行是N个数字D，&nbsp;D[i]表示第i个路口的风险度（1&nbsp;&lt;=&nbsp;D[i]&nbsp;&lt;=&nbsp;100）<BR>接下来的M行，每行两个数字X和Y，表示路口X和路口Y之间有道路相连<BR> 

 
 # 输出格式 
若有解，则输出最少的风险度值。若无解，则输出’NO’（不包含引号） 

 
 # 提示 
样例解释：在1,3,4三个路口上安排刺客，风险度为10+10+25&nbsp;=45<BR> 
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
<tr><td>5 5
10 30 10 25 20
1 2
2 3
2 4
3 5
4 5
</td><td>45</td></tr></table>
