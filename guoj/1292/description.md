
# 题目描述

有两个仅包含小写英文字母的字符串 $ A $ 和 $ B $。现在要从字符串 $ A $ 中取出 $ k $ 个互不重叠的非空子串，然后把这 $ k $ 个子串按照其在字符串 $ A $ 中出现的顺序依次连接起来得到一个新的字符串,请问有多少种方案可以使得这个新串与字符串 $ B $ 相等？

注意：子串取出的位置不同也认为是不同的方案。

# 输入格式

第一行是三个正整数 $ n,m,k $，分别表示字符串 $ A $ 的长度，字符串 $ B $ 的长度，以及问题描述中所提到的 $ k $，每两个整数之间用一个空格隔开。  
第二行包含一个长度为 $ n $ 的字符串，表示字符串 $ A $。  
第三行包含一个长度为 $ m $ 的字符串，表示字符串 $ B $。


# 输出格式

输出共一行，包含一个整数，表示所求方案数。由于答案可能很大，所以这里要求输出答案对 $ 1,000,000,007 $ 取模的结果。

# 样例

#### 样例输入 1
```plain
6 3 1
aabaab
aab
```

#### 样例输出 1
```plain
2
```

#### 样例输入 2
```plain
6 3 2
aabaab
aab
```

#### 样例输出 2
```plain
7
```

#### 样例输入 3
```plain
6 3 3
aabaab
aab
```

#### 样例输出 3
```plain
7
```

# 数据范围与提示

对于第 $ 1 $ 组数据：$ 1 \leq n \leq 500,1 \leq m \leq 50,k = 1 $；  
对于第 $ 2 $ 组至第 $ 3 $ 组数据：$ 1 \leq n \leq 500,1 \leq m \leq 50,k = 2 $；  
对于第 $ 4 $ 组至第 $ 5 $ 组数据：$ 1 \leq n \leq 500,1 \leq m \leq 50,k = m $；  
对于第 $ 1 $ 组至第 $ 7 $ 组数据：$ 1 \leq n \leq 500,1 \leq m \leq 50,1 \leq k \leq m $；  
对于第 $ 1 $ 组至第 $ 9 $ 组数据：$ 1 \leq n \leq 1000,1 \leq m \leq 100,1 \leq k \leq m $；  
对于所有 $ 10 $ 组数据：$ 1 \leq n \leq 1000,1 \leq m \leq 200,1 \leq k \leq m $。
