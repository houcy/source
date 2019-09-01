
# 题目描述

贾樟柯在《山河故人》里说，“生活就是重复”。在生活中，人们总是喜欢重复自己做过的事情。语言就是一个很经典的例子。

比如，我们在表示疑问时，总不满足于使用一个问号“？”；使用一连串的问号“？？？？”总是显得比较有力。

在表示抱歉时，一句“对不起”总显得不够情愿；连着表示“对不起对不起”才足够表达自己的真诚。

A 国就是一个喜欢重复的国家。在这个国家中，一个基本句子可以用一个长度恰好为 $m$ 的小写字母字符串表示。为了表达自己对重复的喜爱， A 国的人们总喜欢把自己想要表达的句子重复无限多次。

有时，这样的重复是充满意义的。 A 国的人们把一个字典序小于给定的字符串 $s$，且长度和 $s$ 相同的小写字母字符串称为一个有意义的语义片段。他们想知道，有多少个不同的基本句子（即长度恰好为 $m$ 的小写字母字符串）在经过无限重复后，可以从中找出至少一个有意义的语义片段？

# 输入格式

从标准输入中读入数据。

输入文件的第一行为一个正整数 $m$，表示基本句子的长度；第二行为一个小写字母字符串 $s$，其含义详见题目描述。

# 输出格式

输出到标准输出中。

输出一行一个整数，为满足条件的基本句子的数量。为了避免答案过大，你只需要输出将答案对 $998244353$ 取模后的结果。

# 样例

#### 样例 1 输入
```plain
3
abc
```

#### 样例 1 输出
```plain
79
```
#### 样例 2 输入
```plain
5
zxcvb
```
#### 样例 2 输出
```plain
11881375
```



# 数据范围与提示

设字符串 $s$ 的长度为 $n$，则 $n$、$m$ 的范围遵循如下表格：

|测试点编号|$m$|$n$|其他限制|
|:-:|:-:|:-:|:-:|
|$1$|$m\le 5$|$n\le 10$|$m<n$|
|$2$|$m\le 30$<!---->|$n\le 30$<!--1-->|$m=n$|
|$3$|$m\le 50$|$n\le 30$|$m>n$|
|$4$|$m\le 100$<!---->|$n\le 100$|$m<n$|
|$5$|$m\le 200$<!---->|$n\le 200$|$m=n$|
|$6$|$m\le 300$<!---->|$n\le 200$<!---->|$m>n$|
|$7$|$m\le 300$|$n\le 2000$|$m<n$|
|$8$|$m\le 1000$|$n\le 1000$|$m=n$|
|$9$|$m\le 2000$<!---->|$n\le 200$|$m>n$<!---->|
|$10$|$m\le 2000$|$n\le 2000$|$m>n$|

对于 $100\%$ 的数据，保证 $1\le n,m\le 2000$。
