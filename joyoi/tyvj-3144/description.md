# 

 
 # 题目描述 
<p>
　　建成于1891年的纽约卡内基音乐厅（Carnegie Hall）音响效果绝佳，是世界最著名的音乐厅之一，它有很大的舞台，在这个音乐季，他们正准备演出莫扎特（Mozart）的歌剧《后宫诱逃（Die Entfuehrung aus dem Serail）》。剧中某些场景需要搭建一座土耳其皇宫，正如我们所熟悉的阿拉伯建筑风格，"皇宫"由一些高度、直径都相同的圆柱支撑，其中一些柱子和外墙相接，另一些在皇宫内部；所有外墙上的柱子向皇宫内的一侧的地面上都放有灯（假设灯放在柱子的圆心这个点上），灯光可以照射到皇宫内的任何部分，除非被东西遮挡。"皇宫"外围是灰白色的"石壁"，就是两根柱子中间的部分，并且总在两根柱子圆心的连线上。墙壁都有一定的透光度，使得内部灯光散射出来，晶莹剔透。因为半透明，墙壁不太厚，相对于柱子的直径，我们忽略墙壁的厚度，如右图所示，灰色部分表示皇宫内部，蓝色部分表示柱子内部。皇宫的横截面总是凸多边形，上方有和横截面几何形状一模一样且厚度密度都均匀的平顶（图中线段围住的部分，即以各个外墙上的柱子的圆心为顶点的凸多边形）。演出时场景布置当然要富丽堂皇、尽善尽美，因此他们请天才的你来解决他们的一切问题。 <br><br>【问题】<br><br>　　1、 舞台上不能放置太重的东西，柱子、墙壁都是用塑料等轻的材料做的，不能承重。而皇宫的平顶面积大，还是挺重的，不能直接压在这些材料上，只能通过舞台顶部的架子悬挂。当然，悬挂用的绳子是越细越少越好。他们提出一个大胆的想法，让你只用一根非常坚固的绳子，悬挂起整个屋顶。你的任务就是，找到平顶上一个恰当的点，使得从这个点可以把平顶平稳的吊起来。 <br><br>　　2、 布景时，布景师们在顶部的架子上走动，时常不小心碰到一些工具，掉下去砸坏了道具。因此，他们观察了几个经常放工具的点，并告诉你这些点在舞台上投影的位置，请你判断一下这些东西竖直掉下会对"皇宫"造成什么影响。某物品从某个点落下，如果恰好砸在柱子上（内），输出C；砸到墙壁上，输出L；砸到皇宫内空地，输出I；落到皇宫外，输出O；如果砸到物体的交界处，只需按照CLIO的顺序输出第一个。<br><br>　　3、 演出时，录音师为演出制作环绕立体声录音。为了排除墙壁隔音的影响，他们在"皇宫"里的地面上也放置了几个麦克风。但为了不影响灯光照射，麦克风必须放在灯光照射不到的地方。出于声学的考虑，录音师建议了几个适合放置麦克风的位置，请你从光学的角度，分析一下其中那些位置可以放置，哪些不可以。如某个麦克风可以放置，那么输出1，否则输出0。<br>　　我们用一个平面直角坐标系表示舞台地面，给你的数据包括：柱子总数、直径，"皇宫"高度，平顶厚度，每根柱子中心的坐标，以及问题2、问题3要判断点的坐标。<br>　　如果你能圆满解决了音乐厅面临的三个难题，演出后，你将被授予"最佳协作奖"。<br></p> 

 
 # 输入格式 
<p>
　　第1行有四个整数，是柱子总数p、直径d、"皇宫"高度h1和平顶厚度h2，数据中间都用一个空格隔开。<br>　　以下p行，每行有两个实数xi ,yi ，数据间用一个空格隔开，是第i根柱子的中心坐标。<br>　　第p+2行是一个整数n，表示问题2要判定的顶点个数。<br>　　以下n行，每行有两个实数xi ,yi ，是问题2要判定的第i个点的坐标，数据间用一个空格隔开。<br>　　第p+n+3行是一个整数m，表示问题3要判定的顶点个数。<br>　　以下m行，每行有两个实数xi ,yi ，数据间用一个空格隔开，是问题3要判定的第i个点的坐标，并保证这些点都在"皇宫"的可用空间内。<br>　　数据范围：1≤p≤1000，0≤n、m≤1000。输入数据不要判错。<br></p> 

 
 # 输出格式 
<p>
　　输入文件必须严格包含三行，分别是三个问题的结果，如果某个问题没有完成，也必须输出一个空行。<br>　　第1行包含两个实数x,y，表示可以悬挂平顶的点的坐标，数据间用一个空格间隔，保留三位小数。<br>　　第2行包括n个字母，是CLIO之一，表示问题2的结果，数据间用一个空格间隔。<br>　　第3行，输出m个数，是0或者1，表示问题3的结果，数字间用一个空格间隔。<br><br></p> 
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
<tr><td>　　7 1 110 10
　　-3 3
　　3 2
　　-2 -2
　　3 -1
　　0 0
　　1 1
　　-1 1
　　4
　　-4 1
　　-2 1
　　0 0
　　0 2.5
　　2
　　1 -1
　　0 0.55

</td><td>　　0.015 0.545
　　O I C L 
　　0 1 </td></tr></table>
