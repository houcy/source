
# 题目描述

**题目译自 [JOISC 2020](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/index.html) Day4 T3「[治療計画](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/day4/treatment.pdf) / [Treatment Project](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/day4/treatment-en.pdf)」**

JOI 国有 $N$ 个房屋，并从 $1$ 到 $N$ 编号。这些房屋沿一条直线升序排列。每个房屋有一个居民住在里面。住在编号为 $x$ 的房屋里的居民用居民 $x$ 表示。

最近，新冠病毒出现了，并且所有居民都被感染了。为了解决这个问题，有 $M$ 个治疗方案被提出。第 $i\ (1\le i\le M)$ 个治疗方案的花费为 $C_i$。如果执行计划 $i$，则会发生以下事件：

- 在第 $T_i$ 天的晚上，如果居民 $x$ 满足 $L_i\le x\le R_i$，且他感染了新冠病毒，那么他就会被治愈。

病毒按如下方式传染相邻的居民：

- 如果在某天的早晨，居民 $x\ (1\le x\le N)$ 被病毒感染，那么在同一天的中午，居民 $x-1$（如果 $x\ge 2$）和居民 $x+1$（如果 $x\le N-1$）就会被感染。

一个已经被治愈的居民可以再次被病毒感染。

你是 JOI 国的首相，你需要选取某些方案，使得满足以下条件：

- 条件：在所有被选中的方案全部执行后，没有居民感染病毒。

在某一天可以执行多个计划。

写一个程序，给定房屋和治疗计划的信息，求出能否满足以上条件，若满足，求出最小可能花费。

# 输入格式

从标准输入中读取以下内容：

第一行两个整数 $N,M$；

接下来 $M$ 行，每行四个整数 $T_i,L_i,R_i,C_i$，表示一个治疗方案。

# 输出格式

输出一行到标准输出。如果条件无法满足，则输出 $-1$，否则输出最小总花费。

# 样例

#### 样例输入 1
```plain
10 5
2 5 10 3
1 1 6 5
5 2 8 3
7 6 10 4
4 1 3 1
```

#### 样例输出 1

```plain
7
```

#### 样例说明 1

在样例 $1$ 中，你可以按照如下方式执行计划：

- 在第二天的晚上，执行计划 $1$，之后居民 $5,6,7,8,9,10$ 被治愈了，现在只有居民 $1,2,3,4$ 被病毒感染；
- 在第三天的中午，居民 $5$ 被病毒感染。现在居民 $1,2,3,4,5$ 被病毒感染；
- 在第四天的中午，居民 $6$ 被病毒感染。现在居民 $1,2,3,4,5,6$ 被病毒感染；
- 在第四天的晚上，执行计划 $5$，之后居民 $1,2,3$ 被治愈了，现在只有居民 $4,5,6$ 被病毒感染；
- 在第五天的中午，居民 $3,7$ 被病毒感染。现在居民 $3,4,5,6,7$ 被病毒感染；
- 在第五天的晚上，执行计划 $3$，之后居民 $3,4,5,6,7$ 被治愈了，现在没有居民被感染了。

执行计划 $1,3,5$ 的总花费为 $7$。并且没有比这个花费更少且满足条件的方案，所以输出 $7$。

#### 样例输入 2
```plain
10 5
2 6 10 3
1 1 5 5
5 2 7 3
8 6 10 4
4 1 3 1
```
#### 样例输出 2
```plain
-1
```
#### 样例说明 2
因为无法满足条件，所以输出 $-1$。

#### 样例输入 3
```plain
10 5
1 5 10 4
1 1 6 5
1 4 8 3
1 6 10 3
1 1 3 1
```
#### 样例输出 3
```plain
7
```
#### 样例说明 3
这组样例满足子任务 1 的限制。

# 数据范围与提示

对于所有数据，满足 $1\le N\le 10^9,1\le M\le 10^5$，保证：

- $1\le T_i,C_i\le 10^9\ (1\le i\le M)$
- $1\le L_i\le R_i\le N\ (1\le i\le M)$

详细子任务及附加限制如下表所示：

| 子任务编号 |        附加限制        | 分值 |
| :--------: | :--------------------: | :--: |
|    $1$     | $T_i=1\ (1\le i\le M)$ | $4$  |
|    $2$     |       $M\le 16$        | $5$  |
|    $3$     |  $M\le 5\times 10^3$   | $30$ |
|    $4$     |       无附加限制       | $61$ |



