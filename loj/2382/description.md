
# 题目描述

小 T 最近在学着买股票，他得到内部消息： F 公司的股票将会疯涨。  
股票每天的价格已知是正整数，并且由于客观上的原因，最多只能为 $N$ 。在疯涨的 $K$ 天中小 $T$ 观察到：除第一天外每天的股价都比前一天高，且高出的价格（即当天的股价与前一天的股价之差）不会超过 $M$，$M$ 为正整数。并且这些参数满足 $M \times (K-1)<N$ 。  
小 T 忘记了这 $K$ 天每天的具体股价了，他现在想知道这 $K$ 天的股价有多少种可能。

# 输入格式

输入只有一行用空格隔开的四个数： $N,K,M,P$ 。  
对 $P$ 的说明参见后面“输出格式”中对P的解释。

# 输出格式

输出仅包含一个数，表示这 $K$ 天的股价的可能种数对于 $P$ 的模值。

# 样例

#### 样例输入
```plain
7 3 2 997
```

#### 样例输出
```plain
16
```

#### 样例解释
输出样例的16表示输入样例的股价有 $16$ 种可能：
```plain
{1，2，3}，{1，2，4}，{1，3，4}，{1，3，5}，
{2，3，4}，{2，3，5}，{2，4，5}，{2，4，6}，
{3，4，5}，{3，4，6}，{3，5，6}，{3，5，7}，
{4，5，6}，{4，5，7}，{4，6，7}，{5，6，7}。
```

# 数据范围与提示

对于所有数据，$1\le n\le 10^{18}, 1\le K, M, P\le 10^9$。

