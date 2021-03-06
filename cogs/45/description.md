# 题目描述


<p>
<b>问题描述</b><br/>
<br/>
错误就是人们所说的Bug。用户在使用软件时总是希望其错误越少越好，最好是没有错误的。但是推出一个没有错误的软件几乎不可能，所以很多软件公司都在疯狂地发放补丁（有时这种补丁甚至是收费的）。T公司就是其中之一。<br/>
<br/>
上个月，T公司推出了一个新的字处理软件，随后发放了一批补丁。最近T公司发现其发放的补丁有致命的问题，那就是一个补丁在排除某些错误的同时，往往会加入另一些错误. <br/>
<br/>
此字处理软件中只可能出现n个特定的错误，这n个错误是由软件本身决定的。T公司目前共发放了m个补丁，对于每一个补丁,  都有特定的适用环境，某个补丁只有在当前软件中包含某些错误而同时又不包含另一些错误时才可以使用，如果它被使用，它将修复某些错误而同时加入某些错误。另外，使用每个补丁都要耗一定的时间（即补丁程序的运行时间）。<br/>
<br/>
<b>准确描述</b><br/>
<br/>
设此字处理软件中可能出现的n个错误为集合B={b1,b2,…,bn}中的元素，T公司目前共发放了m个补丁：p1，p2,…,pm。对于每一个补丁pi,  都有特定的适用环境，某个补丁只有在软件中包含某些错误而同时又不包含另一些错误时才可以用，为了说明清楚，设错误集合：Bi+、 Bi-， 当软件包含了Bi+中的所有错误, 而没有包含Bi-中的任何错误时，补丁Pi才可以被使用，否则不能使用，显然 Bi+、Bi-交集为空。补丁pi将修复某些错误而同时加入某些错误，设错误集合Fi-、Fi+，使用过补丁pi之后，Fi-中的任何错误都不会在软件中出现，而软件将包含Fi+中的所有错误， 同样Fi-、Fi+交集为空。另外，使用每个补丁都要耗一定的时间（即补丁程序的运行时间）。<br/>
现在T公司的问题很简单，其字处理软件的初始版本不幸地包含了集合B中的全部n个错误,  有没有可能通过使用这些补丁（任意顺序地使用，一个补丁可使用多次）， 使此字处理软件成为一个没有错误的软件。如果可能，希望找到总耗时最少的方案。<br/>
<br/>
<b>输入</b><br/>
输入文件第一行有两个正整数n和m,  n表示错误总数，m表示补丁总数，1&lt;=n&lt;=20, 1&lt;=m&lt;=100。接下来m行给出了m个补丁的信息。每行包括一个正整数（表示此补丁程序pi的运行耗时）和两个长度为n的字符串，中间用一个空格符隔开。<br/>
第一个字符串，如果第k个字符为’+’，则表示bk属于Bi+,  若为‘-’，则表示bk属于Bi-, 若为‘0’，则bk 既不属于Bi+也不属于Bi-，即软件中是否包含bk不影响补丁pi是否可用。<br/>
第二个字符串，如果第k个字符为’+’，则表示bk属于Fi+,  若为‘-’，则表示bk属于Fi-, 若为‘0’，则bk 既不属于Fi+也不属于Fi-，即软件中是否包含bk不会因使用补丁pi而改变。<br/>
<br/>
<b>输出</b><br/>
    输出一个整数，如果问题有解，输出总耗时，否则输出0。<br/>
<br/>
<b>输入输出示例</b><br/>
<br/>
<b>输入文件</b><br/>
3 3<br/>
1 000 00-<br/>
1 00- 0-+<br/>
2 0-- -++<br/>
<b><br/>
输出文件</b><br/>
8<br/>
<br/>
<b>样例注释</b><br/>
ABC use 1 to AB_ takes 1<br/>
AB_ use 2 to A_C takes 1<br/>
A_C use 1 to A__ takes 1<br/>
A__ use 3 to _BC takes 2<br/>
_BC use 1 to _B_ takes 1<br/>
_B_ use 2 to __C takes 1<br/>
__C use 1 to ___ takes 1<br/>
<br/>
total 8
</p>
