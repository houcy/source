# 

 
 # 题目描述 
<p>
水管局长（tube.pas/c/cpp)<br><br>【问题描述 】 <br>　　SC 省 MY 市有着庞大的地下水管网络，嘟嘟是 MY 市的水管局长（就是管水管的啦），嘟嘟作为水管局长的工作就是：每天供水公司可能要将一定量的水从 x 处运往 y 处，嘟嘟需要为供水公司找到一条从 A 至 B 的水管的路径，接着通过信息化的控制中心通知路径上的水管进入准备送水状态，等到路径上每一条水管都准备好了，供水公司就可以开始送水了。嘟嘟一次只能处理一项送水任务，等到当前的送水任务完成了，才能处理下一项。 <br><br>　　在处理每项送水任务之前，路径上的水管都要进行一系列的准备操作，如清洗、消毒等等。嘟嘟在控制中心一声令下，这些水管的准备操作同时开始，但由于各条管道的长度、内径不同，进行准备操作需要的时间可能不同。供水公司总是希望嘟嘟能找到这样一条送水路径，路径上的所有管道全都准备就绪所需要的时间尽量短。嘟嘟希望你能帮助他完成这样的一个选择路径的系统，以满足供水公司的要求。另外，由于 MY 市的水管年代久远，一些水管会不时出现故障导致不能使用，你的程序必须考虑到这一点。 <br><br>　　不妨将 MY 市的水管网络看作一幅简单无向图（即没有自环或重边）：水管是图中的边，水管的连接处为图中的结点。 <br><br><br><center><img src="/source/joyoi/tyvj-3462/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQ2Mi9wcm9ibGVtc19pbWFnZXMvMjI3Mi9wLmdpZg==.gif"></img></center><br></p> 

 
 # 输入格式 
<p>
　　输入文件tube.in第一行为 3 个整数： N ， M ， Q 分别表示管道连接处（结点）的数目、目前水管（无向边）的数目，以及你的程序需要处理的任务数目（包括寻找一条满足要求的路径和接受某条水管坏掉的事实）。 <br><br>　　以下 M 行，每行 3 个整数 x ， y 和 t ，描述一条对应的水管。 x 和 y 表示水管两端结点的编号， t 表示准备送水所需要的时间。我们不妨为结点从 1 至 N 编号，这样所有的 x 和 y 都在范围 [1,N] 内。 <br><br>　　以下 Q 行，每行描述一项任务。其中第一个整数为 k ：若 k=1 则后跟两个整数 A 和 B ，表示你需要为供水公司寻找一条满足要求的从 A 到 B 的水管路径；若 k=2 ，则后跟两个整数 x 和 y ，表示直接连接 x 和 y 的水管宣布报废（保证合法，即在此之前直接连接 x 和 y 尚未报废的水管一定存在）。 <br></p> 

 
 # 输出格式 
<p>
　　输出文件tube.out 按顺序对应输入文件中每一项 k=1 的任务，你需要输出一个数字和一个回车 / 换行符。该数字表示：你寻找到的水管路径中所有管道全都完成准备工作所需要的时间（当然要求最短）。 </p> 

 
 # 提示 
<p>
【约束条件】 <br>N ≤ 1000 <br>M ≤ 100000<br>Q ≤ 100000 <br>测试数据中宣布报废的水管不超过 5000 条；且任何时候我们考虑的水管网络都是连通的，即从任一结点 A 必有至少一条水管路径通往任一结点 B 。</p> 
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
<tr><td>4 4 3
1 2 2
2 3 3
3 4 2
1 4 2
1 1 4
2 1 4
1 1 4 
</td><td>
2
3 
</td></tr></table>
