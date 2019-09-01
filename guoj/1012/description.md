
# 题目描述

小$D$喜欢出毒瘤题毒人。当然，他的毒瘤更多体现在若干个难题组合在同一场比赛时。
小$D$脑中有$n$个毒瘤题$idea$，第i个的毒值为$d_i$。当第$i$个题和第$j$个题同时出现在一场
比赛中，会产生$f(i,j)=d_i+d_j$的毒性。
小$D$决定用这些题在$YLOJ$上办$m$场在线比赛。

• 由于这个$OJ$还在咕咕开发，$YLOJ$ $Extremelyhard$ $Round$ $\#i$ 选取的题目编号集合只能为$[l_i,r_i]$的一个非空子区间$[a_i，b_i]$。

• 因为这个$round$是$extremelyhard$的，所以需要满足$\sum\limits_{a_i\le j,k\le b_i}f(j,k)\ge x_i$。

• 不过，为了防止题目过分毒瘤而被喷，小D希望最小化$max_{a_i\le j\le b_i}d_j$，而你需要告诉他这个最小值。

# 输入格式

第一行，正整数$n$，自然数$m$。

第二行，$n$个正整数，第$i$个元素代表$d_i$。

接下来$m$行，每行三个正整数，分别代表$l_i,r_i,x_i$。

# 输出格式

输出$m$行，每行一个整数，代表 $min\{max_{a_i\le j\le b_i}d_j\}$，若没有合法区间，则输出$−1$。

# 样例

#### 样例输入1
```plain
5 2
1 1 2 3 4
1 5 2
1 5 11
```
#### 样例输出1
```plain
1
2
```
#### 样例输入2
```plain
5 4
1 3 2 4 6
1 3 3
1 3 2
2 4 10
1 1 1556528051
```
#### 样例输入2
```plain
2
1
3
-1
```

# 数据范围与提示

保证， $n,m\le 3∗10^5,d_i\le 10^7,1\le l_i\le r_i\le n， x_i\le 10^18$。
