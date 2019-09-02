

# 问题描述


<div class="pdcont">
    聪聪和可可是兄弟俩，他们俩经常为了一些琐事打起来，例如家中只剩下最后一根冰棍而两人都想吃、两个人都想玩儿电脑（可是他们家只有一台电脑）……遇到这种问题，一般情况下石头剪刀布就好了，可是他们已经玩儿腻了这种低智商的游戏。他们的爸爸快被他们的争吵烦死了，所以他发明了一个新游戏：<br/>
    由爸爸在纸上画n个“点”，并用n-1条“边”把这n个“点”恰好连通（其实这就是一棵树）。并且每条“边”上都有一个数。接下来由聪聪和可可分别随即选一个点（当然他们选点时是看不到这棵树的），如果两个点之间所有边上数的和加起来恰好是3的倍数，则判聪聪赢，否则可可赢。<br/>
    聪聪非常爱思考问题，在每次游戏后都会仔细研究这棵树，希望知道对于这张图自己的获胜概率是多少。现请你帮忙求出这个值以验证聪聪的答案是否正确。
</div>

# 输入格式


<div class="pdcont">
    输入的第1行包含1个正整数n。<br/>
    后面n-1行，每行3个整数x、y、w，表示x号点和y号点之间有一条边，上面的数是w。
</div>

# 输出格式


<div class="pdcont">
    以即约分数形式输出这个概率（即“a/b”的形式，其中a和b必须互质。如果概率为1，输出“1/1”）。
</div>

# 样例输入


<pre>5
1 2 1
1 3 2
1 4 1
2 5 3
</pre>

# 样例输出


<pre>13/25
</pre>

# 样例说明



# 试题来源


<p>
2011中国国家集训队命题答辩
</p>