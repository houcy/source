# 题目描述


<p>
	有F (1 &lt;= F &lt;= 5,000)个牧场(标号为：1..F)。奶牛们厌倦了老是走重复的路径。它们想在牧场之间建立一些新的边，使得任意两个牧场至少有两条不同的路径。现在不同的牧场之间已经至少有一条路径了。
</p>
<p>
	给出R (F-1 &lt;= R &lt;= 10,000)条边，每条边连接两个不同的牧场。计算最少需要建立多少条边，使得任意两个牧场之间至少有两条不同的路径。只要没有访问相同的边,那么就可以认为是不同的路径，就算是访问的中间牧场有相同.
</p>
<p>
	注意：两个不同的牧场之间可能有多条不同的边,你依然可以在这两个牧场间建立一条不同的新边。
</p>
<p>
	输入格式：
</p>
<p>
	*第1行:两个不同的整数: F、R
</p>
<p>
	*第2..R+1行:每行两个不同的牧场，表示它们之间有一条边。
</p>
<table>
	<tbody>
		<tr>
			<td>
				<table>
					<tbody>
						<tr>
							<td>
								<p>
									输入解释：
								</p>
<pre class="prettyprint">   1   2   3
   +---+---+ 
       |   |
       |   |
 6 +---+---+ 4
      / 5
     /
    /
 7 +</pre>
								<p>
									<br/>
								</p>
							</td>
						</tr>
					</tbody>
				</table>
样例输入：rpathsa.in
			</td>
		</tr>
	</tbody>
</table>
<pre class="prettyprint">7 7
1 2
2 3
3 4
2 5
4 5
5 6
5 7</pre>
<p>
	<br/>
</p>
<p>
	输出格式：
</p>
<p>
	*一行:  一个整数，算最少需要建立多少条新边，使得任意两个牧场之间至少有两条不同的路径。
</p>
<p>
	样例输出：rpathsa.out
</p>
<pre class="prettyprint">2</pre>
<p>
	输出解释：
</p>
<p>
	在牧场1和6之间建立一条新边，在牧场4和7之间建立一条新边.
</p>
<p>
	<br/>
</p>
<table>
	<tbody>
		<tr>
			<td>
				<table>
					<tbody>
						<tr>
							<td>
								<div>
									<p>
										以下是部分路径（左边是牧场，右边是不同的路径）:
									</p>
									<p>
										1 - 2: 1
    -&gt; 2 and 1 -&gt; 6 -&gt; 5 -&gt; 2
									</p>
									<p>
										1 - 4: 1
    -&gt; 2 -&gt; 3 -&gt; 4 and 1 -&gt; 6 -&gt; 5 -&gt; 4
									</p>
									<p>
										3 - 7: 3
    -&gt; 4 -&gt; 7 and 3 -&gt; 2 -&gt; 5 -&gt; 7
									</p>
									<p>
										你可以发现，任意两个不同牧场之间都至少有两条不同的路径。
									</p>
								</div>
							</td>
						</tr>
					</tbody>
				</table>
<pre class="prettyprint">   1   2   3
   +---+---+ 
   :   |   |
   :   |   |
 6 +---+---+ 4
      / 5  :
     /     :
    /      :
 7 + - - - -</pre>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<br/>
</p>
