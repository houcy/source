<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　丽江河边有 n 家很有特色的客栈，客栈按照其位置顺序从1 到n 编号。每家客栈都按照某一种色调进行装饰（总共k 种，用整数0 ~ k-1 表示），且每家客栈都设有一家咖啡店，每家咖啡店均有各自的最低消费。<br/>
　　两位游客一起去丽江旅游，他们喜欢相同的色调，又想尝试两个不同的客栈，因此决定分别住在色调相同的两家客栈中。晚上，他们打算选择一家咖啡店喝咖啡，要求咖啡店位于两人住的两家客栈之间（包括他们住的客栈），且咖啡店的最低消费不超过p。<br/>
　　他们想知道总共有多少种选择住宿的方案，保证晚上可以找到一家最低消费不超过p元的咖啡店小聚。</div>
# 输入格式

<div class="pdcont">　　输入共n+1 行。<br/>
　　第一行三个整数 n，k，p，每两个整数之间用一个空格隔开，分别表示客栈的个数，色调的数目和能接受的最低消费的最高值；<br/>
　　接下来的 n 行，第i+1 行两个整数，之间用一个空格隔开，分别表示i 号客栈的装饰色调和i 号客栈的咖啡店的最低消费。</div>
# 输出格式

<div class="pdcont">　　输出只有一行，一个整数，表示可选的住宿方案的总数。</div>
# 样例输入

<div class="pddata">5 2 3<br/>
0 5<br/>
1 3<br/>
0 2<br/>
1 4<br/>
1 5</div>
# 样例输出

<div class="pddata">3</div>
# 数据规模和约定

<div class="pdcont">　　对于 30%的数据，有n≤100；<br/>
　　对于 50%的数据，有n≤1,000；<br/>
　　对于 100%的数据，有2≤n≤200,000，0&lt;k≤50，0≤p≤100， 0≤最低消费≤100。</div>

</div>