# 题目描述


<p>
译: zqzas
</p>
<p>
<br/>
没有几个人知道,奶牛有她们自己的字典,里面的有W (1 ≤ W ≤ 600)个词,每个词的长度不超过25,且由小写字母组成.她们在交流时,由于各种原因,用词总是不那么准确.比如,贝茜听到有人对她 说&#34;browndcodw&#34;,确切的意思是&#34;browncow&#34;,多出了两个&#34;d&#34;,这两个&#34;d&#34;大概是身边的噪音.
</p>
<p>
<br/>
奶牛们发觉辨认那些奇怪的信息很费劲,所以她们就想让你帮忙辨认一条收到的消息,即一个只包含小写字母且长度为L (2 ≤ L ≤ 300)的字符串.有些时候,这个字符串里会有多余的字母,你的任务就是找出最少去掉几个字母就可以使这个字符串变成准确的&#34;牛语&#34;(即奶牛字典中某些词 的一个排列).
</p>
<p>
<br/>
输入格式:
</p>
<ul>
<li>
第1行:两个用空格隔开的整数,W和L.
</li>
<li>
第2行:一个长度为L的字符串,表示收到的信息.
</li>
<li>
第3行至第W+2行:奶牛的字典,每行一个词.
</li>
</ul>
<p>
输出格式:
</p>
<ul>
<li>
唯一一行:一个整数,表示最少去掉几个字母就可以使之变成准确的&#34;牛语&#34;.
</li>
</ul>
<p>
样例输入:
</p>
<pre>6 10
browndcodw
cow
milk
white
black
brown
farmer
</pre>
<p>
<br/>
样例输出
</p>
<pre>2
</pre>
<p>
<br/>
</p>