# 

 
 # 题目背景 
2005年是第二次世界大战胜利60周年，让我们的视线回到战火纷飞的年代……<BR>苏德战争爆发后，苏、美、英3国曾多次商讨在西欧开辟第二战场，共同打击法西斯德国的问题。几经周折，1943年11月，苏、美、英3国首脑在德黑兰会议上最终达成协议。1943年圣诞节前夕，美国正式宣布任命艾森豪威尔将军为盟军最高司令，统一指挥盟军在西欧的登陆作战。1944年初，盟军开始进行登陆作战的准备工作。&nbsp;<BR>盟军开辟第二战场的意图是，在法国西北部登陆，夺取登陆场和港口，保障主力上陆和后勤供应，然后发动攻势占领整个法国西北部地区，并与在法国南部登陆的部队配合，向德国内地进攻，协同苏军最后战胜法西斯德国。盟军在比较了3处较为合适的登陆地点后认为，在诺曼底地区登陆条件最优越。<BR>身经百战的敢死队员们这次接受的是一个看似简单但意义重大的任务：占领诺曼底最大的军火仓库。为了配合即将展开的登陆战，防止德军撤退时摧毁仓库设施，队员们要悄悄的取得仓库的控制权——消灭里面的所有敌人。<BR>显然，敌众我寡，但是对于我们训练有素的队员们来说，这并不是一件困难的事情。 

 
 # 题目描述 
仓库是一个m*n的矩形区域，每一格用一个字符来描述：<BR>“.”代表空地;<BR>“#”代表墙或障碍物;<BR>“^”,&nbsp;“v”,&nbsp;“&lt;”,&nbsp;“&gt;”四个字符分别表示正向NSWE四个方向看的敌人。<BR><BR>敌人总是保持固定不动并朝着一个方向看，从这个方向一直延伸直到边界或障碍物的区域是他的视线范围，如果一个敌人没有在任何人的视线范围之内，敢死队员就可以消灭他。你不能消灭一个正在另一个活着的敌人视线范围内的敌人，否则你就会被发现，后果不堪设想。一个敌人不会成为遮挡视线的障碍物。 

 
 # 输入格式 
输入数据的第一行是用空格分开的两个整数n,m&nbsp;，分别表示仓库的长和宽。接下来有n行，每行m个字符，是仓库的描述。 

 
 # 输出格式 
如果能够成功消灭所有敌人，输出消灭所有敌人的不同顺序的数量，否则输出“Impossible”（不含引号）。<BR> 

 
 # 提示 
100%的数据中，1&lt;=m,&nbsp;n&lt;=60<BR>90%的数据中，敌人数不超过10<BR>100%的数据中，敌人数不超过15<BR> 
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
<tr><td>input1:

2 2
>^
#^

input2:

1 3
>.<
</td><td>output1:

2

output2:

Impossible
</td></tr></table>
