# 题目描述


<h3>
【题目描述】<br/>
</h3>
<p>
HHH是T国的公主，平时的一大爱好是作诗。不过这次赶潮流的HHH作了一首英文诗。英文诗的长度为N，用一个仅含有26个小写拉丁字母的字符串表示。HHH把这首诗拿给ORZ欣赏，ORZ突发奇想，想从这首诗中找出一段，使得这一段中出现最多的字母出现的次数与出现最少的字母出现的次数的差值最大。现在请你求出这个最大差值吧。
</p>
<h3>
【输入格式】<br/>
</h3>
<p>
第一行是一个整数N；第二行是一个长度为N的字符串，字符串中只含有26个小写拉丁字母。
</p>
<h3>
【输出格式】<br/>
</h3>
<p>
输出一个整数表示最大差值。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
10 aabbaaabab
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>3</pre>
<h3>
【提示】<br/>
</h3>
<p>
对于40%的数据: N≤5000
</p>
<p>
对于100%的数据: N≤1000000，保证字符串中至少出现两种字母。
</p>
<p>
要注意的是，“出现次数最少的字母”的出现次数不能为0，也就是在选取的那一段中它必须存在。
</p>
<p>
选取aaaba这一段，最大差值为3。
</p>
