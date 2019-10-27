
# Content

>人尽皆知，在喵哈哈村，有一个法力无边的廖神

>他随手一挥，便移走山岳；他随手一指，便填平沟壑；他抬头一望，便斗转星移。

>突然，他嘟嘟嘟的在念着咒语，只听噼啪一声，在喵哈哈村的中心广场就出现一个巨大的矩阵

>村子里的人纷纷称奇。

>好奇的沈宝宝走上前去，看了看这个矩阵。

>这个矩阵是n行m列的矩阵。

>矩阵很大，大到无法无天。

>矩阵很小，小到只有n*3个元素。

>因为，沈宝宝发现了其中的端倪。

>假设T[i][j]表示原矩阵第i行j列的元素大小，那么 T[i][j] = A[i] x j x j + B[i] x j + C[i]

>被人称奇的廖神，笑：“沈宝宝，就算让你看穿这个矩阵又如何？那你能否看出这个矩阵中究竟有多少个K呢？”

>沈宝宝想了想，便轻松解决了这个问题。

>廖神不断地更改K的值，不停的问着

>沈宝宝不停的回答着

>真是神奇。

“啪！坐在窗子边上的陈同学，不要睡觉了！刚才文中提到的沈宝宝，他的每次回答的答案是什么？答不上来，就叫你的家长下午来见我！”，何老师怒道。

陈同学一点都不方，尽管他只记得矩阵的端倪和廖神每次提问的K。就在他站起来的那几秒，他已经口算出答案了。

而你，你知道吗？

# Standard Input

第1行 n,m 表示矩阵n行m列

第2到n+1行 a[i],b[i],c[i]，表示沈宝宝所看出的端倪

第n+2行 Q，表示被人称奇的廖神向沈宝宝提问的次数

第n+3到n+Q+2行，K，表示每次廖神提问的K是什么

我们保证：1<=n<=50000 ,1<=m<=10^9,-10^9<=Ai,Bi,Ci<=10^9,0<=Q<=1000,k<=10^18

以及保证 b[i]\*b[i]-4\*a[i]\*(c[i]-k)在longlong范围内

都是整数~

矩阵都是从1开始的哦~

# Standard Output

Q行答案

每一行一个整数，表示K出现的次数

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
<tr><td>3 3
1 2 3
3 4 5
2 3 4
3
18
7
6</td><td>2
0
1</td></tr></table>


# Constraints



# Note

经过口算，这个矩阵会是这样的：

6 11 18

12 25 44

9 18 31

by qscqesze

# Source

