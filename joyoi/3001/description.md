# 问题描述
   小蛤为了迈向神犇之路，终于决定向一个超恶心的专题——树，发起攻击。他遇
到了一个问题:给你一个n个点，m条无向边的图(保证没有重边)。如果这个图中的若干
个点与连接它们的边组成的一棵树满足n个节点，k个叶子，则我们称这棵树为死亡之
树。求这个图中有多少棵不同的死亡之树？
		叶子的定义:度数为1的节点。
		树相同的定义：如果两棵树所含节点的集合相同，且可以通过摆放，旋转转化为
		另一棵树的形状，我们称之为相同的树。
		如2与1-2-3为一棵树

 / \

1 3
# 输入格式 
第一行三个整数n,m,k代表n个点m条边,最终需要有k个叶子；
接下来m行每行两个整数a,b代表a点与b点有一条边。
# 输出格式
一个整数，代表有多少棵死亡之树。
# 样例输入
4 6 3

1 2

2 3

3 4

4 1

1 3

2 4

# 样例输出
4
# 数据规模及约定
* 对于40%的数据： n ≤ 10,m ≤ 16；
* 对于70%的数据： n ≤ 10,m ≤ 23；
* 对于100%的数据： n ≤ 10,m ≤ 45。