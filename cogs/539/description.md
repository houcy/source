

# 问题描述


<p>
贝希和她的闺密们在她们的牛棚中玩游戏。但是天不从人愿，突然，牛棚的电源跳闸了，所有的灯都被关闭了。贝希是一个很胆小的女生，在伸手不见拇指的无尽的黑暗中，她感到惊恐，痛苦与绝望。她希望您能够帮帮她，把所有的灯都给重新开起来！她才能继续快乐地跟她的闺密们继续玩游戏！
</p>
<p>
牛棚中一共有N（1 &lt;= N &lt;= 35）盏灯，编号为1到N。这些灯被置于一个非常复杂的网络之中。有M（1 &lt;= M &lt;= 595）条很神奇的无向边，每条边连接两盏灯。
</p>
<p>
每盏灯上面都带有一个开关。当按下某一盏灯的开关的时候，这盏灯本身，还有所有有边连向这盏灯的灯的状态都会被改变。状态改变指的是：当一盏灯是开着的时候，这盏灯被关掉；当一盏灯是关着的时候，这盏灯被打开。
</p>
<p>
问最少要按下多少个开关，才能把所有的灯都给重新打开。
</p>
<p>
数据保证至少有一种按开关的方案，使得所有的灯都被重新打开。
</p>
<p>
题目名称：lights
</p>
<p>
输入格式：
</p>
<p>
＊第一行：两个空格隔开的整数：N和M。
</p>
<p>
＊第二到第M+1行：每一行有两个由空格隔开的整数，表示两盏灯被一条无向边连接在一起。<br/>
没有一条边会出现两次。
</p>
<p>
样例输入（文件 lights.in）：
</p>
<p>
5 6<br/>
1 2<br/>
1 3<br/>
4 2<br/>
3 4<br/>
2 5<br/>
5 3
</p>
<p>
输入细节：
</p>
<p>
一共有五盏灯。灯1、灯4和灯5都连接着灯2和灯3。
</p>
<p>
输出格式：
</p>
<p>
第一行：一个单独的整数，表示要把所有的灯都打开时，最少需要按下的开关的数目。
</p>
<p>
样例输出（文件 lights.out）：
</p>
<p>
3
</p>
<p>
输出细节：
</p>
<p>
按下在灯1、灯4和灯5上面的开关。
</p>