
# Content

纯音乐，请您欣赏。

——《[未使用曲 2 (Song for friends -instrumental Ver.-)](https://music.163.com/song?id=26089123)》

~~这该死的网易云怎么没有 ED 的~~

~~算了那就换个 ED 好了~~

---

美食殿堂工会的活动经费不足，疫情期间工会管理处没有任务，毕竟魔物也要居家隔离。四人想了想，发现做外卖可能很挣钱，于是他们就做起了外卖生意（由初音提供配送服务）。

他们一共会做 $n$ 种菜品，每种菜品售价 $v_i$。但是在兰德索尔，因为霸瞳皇帝的控制和科技落后，人们没多少钱。虽然人是要恰饭的嘛，但是他们只会挑最便宜的几种菜品买。

兰德索尔气人外卖 App 妈饿了（由可可萝代言）设计比较奇怪，每次显示店家出售菜品信息时，这个 App 只会显示所有菜品中的一些（当然不会不显示任何菜品）。兰德索尔居民只会选择显示的菜品中最便宜的 $k$ 种买，每种买一份。如果显示的少于 $k$ 种菜品，他们就会全部买下。

对于这个 App 所有显示菜品的情况，定义其价值为兰德索尔居民将要付的钱。现在凯露想知道，对于 $\forall i\in [1,n]\cap\mathbb{N}$，当 $k=i$ 时所有显示菜品情况的价值和。

# Standard Input

第一行一个正整数 $n$，意义如题目描述；

接下来一行 $n$ 个数，第 $i$ 个数表示 $v_i$。

# Standard Output

输出 $n$ 行，第 $i$ 行表示当 $k=i$ 时所有显示菜品情况的价值和，请对 $998244353$ 取模后输出。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3
1 3 2</td><td>11
21
24</td></tr><tr><td>6
1 1 4 5 1 4</td><td>85
222
376
474
507
512</td></tr></table>


# Constraints

$1\le n\le 2\times 10^5,1\le v_i<998244353$

# Note

所有菜品显示情况（用下标表示）为：$\{1\},\{2\},\{3\},\{1,2\},\{1,3\},\{2,3\},\{1,2,3\}$，共 $7$ 种。

当 $k=1$ 时，所有菜品显示情况的价值和为 $1+3+2+1+1+2+1=11$；

当 $k=2$ 时，所有菜品显示情况的价值和为 $(1)+(3)+(2)+(1+3)+(1+2)+(2+3)+(1+2)=21$；

当 $k=3$ 时，所有菜品显示情况的价值和为 $(1)+(3)+(2)+(1+3)+(1+2)+(2+3)+(1+2+3)=24$。

取模后仍为对应值。

# Source


