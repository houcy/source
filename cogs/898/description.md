
<!--题目名称： 天才麻将少女什么编
文件名称： sakinani
题目难度： 2
时间限制： 1 s
空间限制： 256 MiB
测试点数： 10
评测方法： 过滤换行回车
-->

# 咲



# 怜


<h3>
题目要求
</h3>
<p>
我们给出一个人物列表，人物有其所属的学校。比如「松実玄」同学隶属「阿知賀女子学院」什么的。有的人物没有所属学校或没有明确给出其所属，可以无视。
</p>
<p>
人物每一次出场都会给其学校增加一点存在感。有少数“被牌爱着的孩子”，即“魔物”会有非常高的存在感，出场一次会有普通人出场两次的存在感。
</p>
<p>
我们需要统计，在给出的人物出场单中，哪个学校存在感最高，我们就把这篇动画命名为什么编。
</p>
<h3>
输入格式
</h3>
<ul>
<li>
输入文件第一行为一个整数 n ，表示有多少人物出现。下面 n  行是人物列表，每两行有两个字符串 A 和 B ，表示人物 A 属于学校 B 。没有同名人物，不会重复出现人物。
</li>
<li>
下面一行一个整数 k ，表示魔物的数量。接下来 k  行，每行一个字符串，表示魔物的姓名，不保证魔物在人物列表中。
</li>
<li>
接下来直到文件末尾，每行有一个字符串（空行不算），表示出场人物，可能会出现不存在于上面列表中的人物。
</li>
</ul>
<h3>
样例输入
</h3>
<pre>7
宮永咲 清澄高校
原村和 清澄高校
片岡優希 清澄高校
園城寺怜 千里山女子高校
竹井久 清澄高校
天江衣 龍門渕高校
龍門渕透華 龍門渕高校
2
宮永咲
天江衣

原村和
高鴨穏乃
原村和
片岡優希
原村和
宮永咲</pre>
<h3>
输出格式
</h3>
<ul>
<li>
输出只有一行，即存在感最大的学校名称，并列第一则输出编码序小的一个。
</li>
</ul>
<h3>
样例输出
</h3>
<pre>清澄高校</pre>
<h3>
数据范围及要求
</h3>
<ul>
<li>
对于 70% 的数据，总出现次数不超过 10000。
</li>
<li>
对于 100% 的数据，学校数量不超过 40 ，人物数量不超过 200 ，总出现次数不超过 1000000。
</li>
</ul>
<ul>
<li>
对于 40% 的数据，字符串中只有大写和小写字母。
</li>
<li>
对于 100% 的数据，字符串中会存在大小写字母、汉字和日语假名，且长度不超过 100 。为了简化问题，输入输出文件都使用 ANSI 编码（一个东亚字符占两字节）。
</li>
</ul>