
# 题目描述

设函数 $f(x)$ 满足 $f(0)=0$ ，且对任意正整数 $x$ 有
$$f(x)=
\begin{cases}
f(x-1)+1, & x \ mod \ 2 =  1 \\
f(\frac{x}{2}), &  x \  mod \ 2 = 0
\end{cases}$$

求

$$\sum_{i=1}^n{f(i)}$$

# 输入格式

一行一个整数 $n(1\leq n \leq 10^9)$。

# 输出格式

一行一个整数表示结果。

# 样例

#### 样例输入

``` plain
3
```

#### 样例输出

``` plain
4
```

# 数据范围与提示



