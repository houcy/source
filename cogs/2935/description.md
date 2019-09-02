# 题目描述


<h3>
题目描述
</h3>
<p>
小 C 非常擅长背包问题，他有一个奇怪的背包，这个背包有一个参数 $P$，当他向这个背包内放入若干个物品后，背包的重量是物品总体积对 $P$ 取模后的结果。
</p>
<p>
现在小 C 有 $n$ 种体积不同的物品，第 $i$ 种占用体积为 $V_i$，每种物品都有无限个。他会进行 $q$ 次询问，每次询问给出重量 $w_i$，你需要回答有多少种放入物品的方案，能将一个初始为空的背包的重量变为 $w_i$。注意，两种方案被认为是不同的，当且仅当<u>放入物品的种类不同</u>，而与每种物品放入的个数无关。不难发现总的方案数为 $2^n$。
</p>
<p>
由于答案可能很大，你只需要输出答案对 $10^9+7$ 取模的结果。
</p>
<h3>
输入格式
</h3>
<p>
从文件 $knapsack.in$ 中读入数据。
</p>
<p>
第一行三个整数 $n,q,P$。
</p>
<p>
接下来一行 $n$ 个整数表示 $V_i$。
</p>
<p>
接下来一行 $q$ 个整数表示 $w_i$。
</p>
<h3>
输出格式
</h3>
<p>
输出到文件 $knapsack.out$ 中。
</p>
<p>
输出 $q$ 行，每行一个整数表示答案。
</p>
<h3>
样例输入
</h3>
<pre>3 3 6
1 3 4
5 2 3
</pre>
<h3>
样例输出
</h3>
<pre>5 
6
6
</pre>
<h3>
样例解释
</h3>
<p>
对于第一个询问 $5$，选择 $\{1\},\{1,3\},\{1,4\},\{3,4\},\{1,3,4\}$ 都是合法的方案。
</p>
<h3>
数据范围与约定
</h3>
<p>
对于所有数据，有 $1\le n, q\le 10^6, 3\le P\le 10^9, 0\lt V_i,w_i\lt P$。
</p>
<p>
保证 $V_i$ 两两不同。
</p>
<p>
<img src="/upload/image/20180424/20180424125115_10133.jpg" alt=""/> 
</p>
<p>
<img src="/upload/image/20180424/20180424125258_36773.jpg" alt=""/> 
</p>
<p>
<img src="/upload/image/20180424/20180424125309_54578.jpg" alt=""/> 
</p>
<p>
<img src="/upload/image/20180424/20180424125318_70130.jpg" alt=""/> 
</p>