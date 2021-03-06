<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在洛丹伦大陆上，首都传来的消息让每个人都感到恐惧。带领人类军团在北方打败不死族的英雄——阿尔萨斯王子，居然刺杀了他的父亲，然后销声匿迹。在前线作战的人类士兵们失去了斗志，不死族士兵乘机进攻，打败了人类防军。洛丹伦的人类王国，剩下的只有昔日的荣耀。<br/>
　　已成为死亡骑士的阿尔萨斯决定在洛丹伦上建立起不死族的基地。洛丹伦的地图可以看做一个N行N列的方格图，某些方格中是无法利用的山地，其余的方格中为空地。空地中一部分已经变成了腐地，另一部分仍然是人类的土地。因为不死族只能在腐地上建造建筑物，所以阿尔萨斯必须想办法将所有的空地变为腐地。<br/>
　　阿尔萨斯决定在洛丹伦大陆上施放若干次“魔法波”。每次施放“魔法波”需要选择地图中一个代表空地（腐地或人类的土地）的格子。从这个格子出发，向上下左右四个方向发出4道魔法波，魔法波会一直朝一个方向运动，直到到达一个代表山地的格子或者移动到大陆之外。对于所有魔法波经过的格子（包括出发点的格子），其中人类的土地会变为腐地，但是腐地会变回人类的土地。需要注意的是，尽管4道魔法波都是从同一个格子出发的，但这个作为出发点的格子只会受到一次魔法的影响。此外，对于某一个格子，从这个格子出发，最多只能施放1次魔法波。<br/>
<br/>
　　以下是一个示例（用&#34;X&#34;代表山地，&#34;1&#34;代表腐地，&#34;0&#34;代表人类的土地）：<br/>
　　初始时的地图如下：<br/>
　　00X1<br/>
　　0X01<br/>
　　1000<br/>
　　010X<br/>
　　如果在第2行第3列（行列均从1开始计数）施放“魔法波”，则施放完毕后的地图如下：<br/>
　　00X1<br/>
　　0X10<br/>
　　1010<br/>
　　011X<br/>
　　注意到第2行第1列的格子并没有变化，因为第2行第2列的山地阻挡了向左的魔法波。<br/>
<br/>
　　现在阿尔萨斯王子需要找到一种施法方案，使得洛丹伦大陆上所有空地都变为腐地。在本题中，你可以假设这样的方案一定存在。</div>
# 输入格式

<div class="pdcont">　　第一行包含一个数N，代表方格的行数和列数。<br/>
　　以下N行，每行包含N个字符，描述了洛丹伦大陆的地图。大写字母&#34;X&#34;代表山地，数字&#34;1&#34;代表腐地，数字&#34;0&#34;代表人类的土地。</div>
# 输出格式

<div class="pdcont">　　输出包含N行，每行包含N个字符。数字&#34;1&#34;表示需要以这个格子为出发点施放一次魔法波，数字&#34;0&#34;则表示不需要。对于所有代表山地的格子，相应的字符必须为&#34;0&#34;。<br/>
　　只需要给出任意一个满足要求的方案，就可以得到这个测试点的所有分数。</div>
# 样例输入

<div class="pddata">4<br/>
00X1<br/>
0X01<br/>
1000<br/>
010X</div>
# 样例输出

<div class="pddata">1000<br/>
0000<br/>
0010<br/>
0000</div>
# 数据规模和约定

<div class="pdcont">　　10%的数据满足N≤5；<br/>
　　30%的数据满足N≤30；<br/>
　　100%的数据满足N≤800，且地图中代表山地的格子不超过200个。</div>

</div>