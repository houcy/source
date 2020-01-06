
# 题目描述

 **译自 [COCI 2010.04](http://hsin.hr/coci/archive/2009_2010/) T6.** ***[RESTORAN](http://hsin.hr/coci/archive/2009_2010/contest7_tasks.pdf)***

给一张有 $N$ 个点 $E$ 条无向边的图，请给边染上红色或绿色，使得任何一个度数 $\ge 2$ 的点都能连接两种颜色的边。若无解，请输出 $0$。

# 输入格式



# 输出格式

若有解，请按照边的输入顺序来输出每条边的颜色，$1$ 为红色，$2$ 为绿色。  
若无解，请输出 $0$。

# 样例

#### 样例输入 1
```plain
5 6
1 2
2 3
3 1
3 4
1 4
4 5
```
#### 样例输出 1
```plain
1
2
1
2
2
1
```
#### 样例输入 2
```plain
7 7
1 2
2 3
3 1
4 5
5 6
6 7
7 4
```
#### 样例输出 2
```plain
0
```
#### 样例输入 3
```plain
77777 4
1 2
1 3
1 4
1 5
```
#### 样例输出 3
```plain
1
2
2
2
```

# 数据范围与提示

对于 $60\%$ 的数据，$N\le 1000,$ $E\le 5000$.  
对于所有数据，$1≤N,$ $E≤10^5$.
