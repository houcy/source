# 题目描述

<p>小M至上主义者小D今天心情很好，准备给小M准备一个圣诞礼物。</p>
<p>他购买了一个圣诞树，这个圣诞树是一个有 $n$ 个点的树，点 $i$ 有一个颜色 $c_i$。小D觉得如果某种颜色太多就不好看了，所以最多会有 $5$ 个点有相同的颜色。</p>
<p>小M收到了礼物很高兴，但是她最近对计数问题很感兴趣，于是她有一些问题想要小D解决。每次小M会关心三种不同的颜色 $a,b,c$，她想要知道这个圣诞树有多少个不同的<strong>非空联通子图</strong>满足里面颜色为 $a,b,c$ 的点的个数分别为 $n_a,n_b,n_c$。由于数可能很大，输出关于对 $10^9+7$ 取模的余数就可以了。</p>
<p>小D当然轻松解决了这个问题，你虽然被喂了狗粮，但你也想锻炼你的实力，你能解决这个问题吗？</p>
# 输入格式


<p>第一行两个数 $n$ 和 $Q$，表示树的大小和询问的个数。
第二行 $n$ 个数，其中第 $i$ 个表示 $c_i$，为第 $i$ 个节点的颜色。
接下来 $n-1$ 行，每行两个数 $a$ 和 $b$，表示点 $a$ 和点 $b$ 之间有一条边。
接下来 $Q$ 行，其中每行有 $6$ 个数 $a,n_a,b,n_b,c,n_c$，表示如题目中所述的询问。</p>
# 输出格式


<p>对每个询问输出一行表示答案。</p>
# 样例一


<h4>input</h4>
<pre>5 3
1 2 3 1 2
1 2
2 3
3 4
4 5
1 1 2 1 3 1
1 0 2 1 3 1
1 1 2 1 3 0
</pre>

<h4>output</h4>
<pre>3
1
2
</pre>

# 限制与约定


<p>对于每个 $ 1 \le i \le n$, $1 \le c_i \le n$。</p>
<p>对于每个询问我们有: $0 \le n_a,n_b,n_c \le 5$, $1 \le a,b,c \le n$ 以及 $a,b,c$ 两两不同。</p>
<p>对于 $10\%$ 的询问, $n,Q \le10$。</p>
<p>对于另 $10\%$ 的询问, $n\le15,Q\le50$。</p>
<p>对于另 $10\%$ 的询问, $n,Q \le1000$。</p>
<p>对于另 $5\%$ 的询问, $n,Q \le 50000$，并且输入的树如果以点 $1$ 为根，最大深度不超过 $35$（点 $1$ 的深度为 $0$）。</p>
<p>对于另 $5\%$ 的询问, $n,Q \le 100000$，并且输入的树如果以点 $1$ 为根，最大深度不超过 $35$（点 $1$ 的深度为 $0$）。</p>
<p>对于另 $20\%$ 的询问, $n,Q \le 100000$，并且保证所有询问 $ (n_a + 1)^2 \cdot (n_b + 1)^2 \cdot (n_c + 1)^2$ 的和小于等于 $10^{8}$。</p>
<p>对于另 $40\%$ 的询问, $n,Q \le 100000$，并且保证所有询问 $ (n_a + 1)(n_b + 1)(n_c + 1)$ 的和小于等于 $8 \cdot 10^{6}$。</p>
<p><strong>时间限制：</strong>$4\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>
# 下载


<p><a href="/download.php?type=problem&amp;id=271">样例数据下载</a></p>