# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
世博会(刘洪轩)
</div>
<div style="text-align:center;font-size:14px;vertical-align:middle;" id="pres">
<div style="font-weight:bold;margin:8px 0px 6px;">
时间限制：<span style="text-decoration:underline;">2.0s</span>   内存限制：<span style="text-decoration:underline;">256.0MB</span> 
</div>
</div>
<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【题意描述】
</h3>
<div class="pdcont">
感谢HQ提供题目描述<br/>
四年一度的世博会又要举办了，Q国很荣幸成为了这次世博会的主办方。Q国主席QQ从全国各地收集了N件物品排成一排，作为Q国馆的展出物。<br/>
对于相邻摆放的一些物品，如果过于相似会让人觉得无聊，如果差别过大又会让人觉得突兀。为了让人们对这次世博会的展出满意，QQ需要知道一些相邻物品的“差异度”。为了方便表示，QQ给每个物品都定义了两个属性值A、B，两件物品之间的“绝对差异值”定义为它们对应属性的差的绝对值较大的一个。对于一些物品的“差异度”，类似求方差的方法，QQ总会首先设想一个理想的“平均物品”，它的两个属性可以为任意实数，且它与这些物品中的每个物品的“绝对差异值”之和最小。而这些物品的“差异度”就定义为这个最小的和。QQ每次会询问：从第Li个到第Ri个物品的“差异度”是多少。现在，这个任务交给了神犇你。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行两个整数N和Q，表示物品数和QQ的询问数。<br/>
第二行N个整数A1到An，表示每个物品的A属性。<br/>
第三行N个整数B1到Bn，表示每个物品的B属性。<br/>
之后Q行每行两个整数Li Ri，表示QQ的询问。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
共Q行，每行输出一个数，表示该次询问的物品的差异度，结果保留到小数点后两位。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
4 2<br/>
1 6 -3 2<br/>
2 7 -1 3<br/>
1 4<br/>
2 3<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
10.00<br/>
9.00<br/>
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
对于第一个询问，平均物品的两个属性可以是1和2<br/>
差异度为max(0,0)+max(5,5)+max(4,3)+max(1,1)=10<br/>
对于第二个询问，平均物品的两个属性可以是6和7<br/>
差异度为max(0,0)+max(9,8)=9<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于10%的数据，1&lt;=N&lt;=100, Q=1且L1=1, R1=N, |Ai|,|Bi|&lt;=100<br/>
对于20%的数据，1&lt;=N&lt;=1000, 1&lt;=Q&lt;=10, |Ai|,|Bi|&lt;=1000000<br/>
对于40%的数据，1&lt;=N&lt;=10000, 1&lt;=Q&lt;=500, |Ai|,|Bi|&lt;=1000000<br/>
对于60%的数据，1&lt;=Q&lt;=500<br/>
对于100%的数据，1&lt;=N&lt;=100000, 1&lt;=Q&lt;=100000, |Ai|,|Bi|&lt;=1000000000<br/>
对于100%的数据，1&lt;=Li&lt;=Ri&lt;=N<br/>
</div>
</div>
