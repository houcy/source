
# Description

<div class="content"><div>Farmer John has received a shipment of N large hay bales (1≤N≤100,000), and placed them at various locations along the road</div>
<div>connecting the barn with his house. Each bale j has a size Sj and a distinct position Pj giving its location along the one-dimensional</div>
<div>road. Bessie the cow is currently located at position B, where there is no hay bale.</div>
<div>Bessie the cow can move around freely along the road, even up to the position at which a bale is located, but she cannot cross</div>
<div>through this position. As an exception, if she runs in the same direction for D units of distance, she builds up enough speed to</div>
<div>break through and permanently eliminate any hay bale of size strictly less than D. Of course, after doing this, she might open up</div>
<div>more space to allow her to make a run at other hay bales, eliminating them as well.</div>
<div></div>
<div>FJ is currently re-painting his house and his barn, and wants to make sure Bessie cannot reach either one (cows and fresh paint</div>
<div>do not make a good combination!) Accordingly, FJ wants to make sure Bessie never breaks through the leftmost or rightmost hay</div>
<div>bale, so she stays effectively trapped within the hay bales. FJ has the ability to add hay to a single bale of his choosing to help</div>
<div>keep Bessie trapped. Please help him determine the minimum amount of extra size he needs to add to some bale to ensure Bessie</div>
<div>stays trapped.</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">农夫约翰将N(1&lt;=N&lt;=100000)堆干草放在了一条平直的公路上。第j堆干草的大小为Sj，坐标为Pj。奶牛贝茜位于一个没有干草堆的点B。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">奶牛贝茜可以在路上自由移动，甚至可以走到某个干草堆上，但是不能穿过去。但是如果她朝同一个方向跑了D个单位的距离，那么她就有足够大的速度去击碎任何大小严格小于D的干草堆。当然，在这之后如果她继续朝着该方向前进，那么她的速度不会清零。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">约翰可以指定某堆干草，并增大它的大小，他想知道他最少需要增大多少，才能把奶牛贝茜困住，或者根本不可能。</div>
</div>
<div></div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;"></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N as well as Bessie&#39;s initial position B. Each of the next N lines describes a bale, and</div>
<div>contains two integers giving its size and position. All sizes and positions are in the range 1…109.</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Print a single integer, giving the minimum amount of hay FJ needs to add to prevent Bessie from escaping.</div>
<div>Print -1 if it is impossible to prevent Bessie&#39;s escape.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
8 1<br/>
1 4<br/>
3 8<br/>
12 15<br/>
20 20</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供译文 Silver">鸣谢Claris提供译文 Silver</a></p></div>

