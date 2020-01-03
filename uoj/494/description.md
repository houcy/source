# 题目描述


# Description


<p>2018年10月，MIT建立了最新的纳米科技研究中心MIT.nano。此后，不断有新的研究成果在此产生。</p>
<p>有一天，研究者发现了一种新的生物，这种生物的基因中含有$n$条DNA序列，每一条都有一定的长度，科学家们可以将每条DNA序列切断，从而取出它的一个<strong>非空前缀</strong>。此后，他们可以将这些前缀按<strong>任意顺序</strong>连结起来形成一条完整的DNA序列，这样的DNA序列对治疗癌症有很大的作用。</p>
<p>每条DNA序列都仅包含大写字母“A”，“C”,“G”，“T”。</p>
<p>科学家们很快发现，DNA序列的字典序越小，则治疗癌症的效果越好，他们想知道给定$n$条DNA序列，他们能获得的字典序最小的DNA序列是什么。</p>

# Task


<h4>Input</h4>
<p>第一行一个正整数$n$，表示DNA序列的个数。</p>
<p>接下来$n$行，每行一个非空字符串表示一条DNA，保证每个字符均为“A”，“C”,“G”，“T”中的一个。</p>
<h4>Output</h4>
<p>输出一行一个字符串，表示能获得的字典序最小的DNA序列。</p>

# Sample 1


<pre><code>5
AGT
GTA
ATC
GGGGG
CAT</code></pre>
<pre><code>AACAGG</code></pre>

# Explanation


<p>五条DNA序列分别取前缀“A”，“G”，“A”，“G”，“CA”，按照“A+A+CA+G+G”的顺序拼接起来即可获得答案。</p>

# Sample 2


<p>见<a href="http://uoj.ac/download.php?type=problem&amp;id=494">样例数据下载</a>，满足存在一种最优解是按照1到$n$的顺序。</p>

# Constraint


<p>设$m$为所有字符串长度的最大值。</p>
<p>对于 $10\%$ 的数据，$m = 1$。</p>
<p>对于 $30\%$ 的数据，$n, m \le 7$。  </p>
<p>对于另外 $30\%$ 的数据，满足存在一种最优解是按照1到$n$的顺序。</p>
<p>对于 $100\%$ 的数据，$1 \le n, m \le 50$。</p>
<p>时间限制2s，空间限制2G。</p>

# Brief Description of the Standard Solution


<p><a href="http://matthew99.blog.uoj.ac/blog/5352">http://matthew99.blog.uoj.ac/blog/5352</a></p>