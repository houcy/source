<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　你带着你的宠物狗去公园玩，你为了训练它，在地上一些位置放了一些玩具。你的宠物狗已经能够完成按照某个特定次序捡起所有玩具这样的任务。为了防止它在捡完所有玩具后乱跑，你用一个绳子拴着它，并且另外一端钉在了地上。但是，公园里面有一些树，并且你的宠物狗在捡到一个玩具后，只会沿着直线跑向下一个玩具。于是，就有可能出现绳子绕在树上的情况。你想知道，你的绳子至少要多长才能够使得它能够按照顺序捡起所有玩具。<br/>
　　此外，输入数据保证，宠物狗的路线上任意一点离每一棵树的距离都至少为0.001。当它需要跑过之前的绳子时，它一定会向上跨过，因此，绳子本身不会打结。所有的树的半径非常小，可以认为是一个点。开始时，宠物狗在(0,0)，并且它也被拴在这个点上，所有的绳子都在这附近并且没有打结。</div>
# 输入格式

<div class="pdcont">　　第一行一个数T，表示共有T组数据，接下来描述每组数据的输入。<br/>
　　每组数据的第一行两个整数N,M，N表示玩具的个数，M表示树的个数。接下来N行，每行一个坐标依次表示所有玩具的位置，宠物狗会按照输入的顺序捡起所有玩具。再接下来M行，每行一个坐标，表示在这个位置上有一棵树。</div>
# 输出格式

<div class="pdcont">　　对于每组数据输出一行一个数，表示最短的绳子长度，四舍五入至小数点后两位。</div>
# 样例输入

<div class="pddata">2<br/>
8  4<br/>
2  -1<br/>
3  0<br/>
3  2<br/>
0  1<br/>
3  2<br/>
3  0<br/>
2  -1<br/>
0  0<br/>
1  0<br/>
2  0<br/>
1  1<br/>
2  1<br/>
8  4<br/>
2  -1<br/>
3  0<br/>
3  2<br/>
0  1<br/>
3  2<br/>
3  0<br/>
2  -1<br/>
0  0<br/>
1  0<br/>
2  0<br/>
1  1<br/>
2  1</div>
# 样例输出

<div class="pddata">5.00<br/>
5.00</div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据，M=0。<br/>
　　对于30%的数据，0&lt;=M&lt;=1。<br/>
　　对于100%的数据，0&lt;=M&lt;=50,1&lt;=N&lt;=50，所有坐标均为整数且绝对值不超过1000。</div>

</div>