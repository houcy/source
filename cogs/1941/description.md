# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
贝茜和她的朋友们在每年的Superbull冠军赛玩hoofball，农民约翰负责组织比赛，要使比赛尽可能精彩。共有N（1≤N≤2000）队参加superbull比赛。每队分配1个不同的整数ID（范围在 1……2^30-1）以区分不同的球队。这个superbull的每一场比赛都是一个淘汰赛，农民约翰选择哪一队从superbull中被淘汰。这个superbull结束时，只剩下一个团队仍然存在。
</p>
<p>
农民约翰注意到比赛的得分有一个非常不寻常的特性！任何一场比赛，两支球队的综合得分总是以两队ID号按位异或（XOR）的值结束。
</p>
<p>
例如，如果两队的ID分别是12和20，那这场比赛的得分将是24点，即 01100 XOR 10100 = 11000。
</p>
<p>
农民约翰相信一场比赛的得分可以得更多的点，该比赛才更精彩。因此，他要选择一个合适的比赛序列，使superbull的总得分最大化。请帮助农民约翰组织比赛。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行包含一个整数n
</p>
<p>
以下N行包含N组ID。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个的最大可能整数，superbull比赛中总的得分点数
</p>
<h3>
【样例输入】
</h3>
<pre>4
3
6
9
10</pre>
<h3>
【样例输出】
</h3>
<pre>37</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
样例说明：
</p>
<p>
取得37分的一个方案如下：FJ先组织3号球队和9号球队比赛，并判定9号队胜，则6号，9号，和10号留下继续比赛。然后他再选6和9比赛，并让6号胜。则6号和10号留下继续比赛。最后，6号和10号比赛，10号胜。总得分点数是（3 XOR 9）+（6 XOR 9）+（6 XOR 10）= 10 + 15 + 12 = 37。
</p>
<p>
注：按位异或运算，通常用^符号，它是对两个二进制整数的每一位按位执行逻辑异或运算。异或运算的规则是：只有在两个比较的位不同时其结果是1，否则结果为0
</p>
<p>
例如：10100（十进制的20）XOR
</p>
<p>
01100（十进制12）= 11000（十进制的24）
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
