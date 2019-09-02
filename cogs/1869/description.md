
<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->

# 试题来源


<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">

# 问题描述


<div class="pdcont">
雨荨的班主任安远老师是一个非常严厉的老师。到了大学，男生和女生之间难免会出现一些暧昧关系，但这样显然是影响学习的。所以作为艾利斯顿的一块招牌，安远老师当然要拒绝这种现象的出现以及繁衍。<br/>
所以每当安远老师发现一个男生和一个女生放学走在一起或者男女生之间互相传纸条等，他就会立马制止并且通知家长。他也要求所有男女生晚上八点之后必须关手机，并且不定期打电话检查。于是安远老师的学生都感慨：这货不是大学，不是大学。<br/>
安远老师的学生里，一共有n个男生和n个女生，编号都以1~n编号。有m对男女生之间有暧昧关系。现在安远老师想找出这样一个男女生群体，每个男生都和每个女生之间有暧昧关系，并且男女生总数最大。注意，男生数目或者女生数目可以为0。如果有多个这样的群体，安远老师会选择男生最多的那个群体，因为他觉得男生会很不安分。如果这样的群体依然不唯一，他会选择任意一个。<br/>
接下来，安远老师从选出的这个群体的所有暧昧关系中，选出k个进行调查，使得这个群体的所有男生和女生，都至少和其中的一对暧昧关系有关系（即是这个暧昧关系的男/女主人公）。安远老师想让你告诉他，总方案数除以19921228的余数是多少。
</div>

# 输入格式


<div class="pdcont">
输入为标准输入。<br/>
输入的第一行包含两个正整数n和k，分别代表男生女生的个数，以及安远老师要选择的暧昧关系个数。<br/>
第二行为一个正整数m，代表暧昧关系总个数。<br/>
接下来m行，每行两个整数，代表一对有暧昧关系的男女生编号。
</div>

# 输出格式


<div class="pdcont">
输出为标准输出。<br/>
第一行有两个空格隔开的整数，代表选择的团体内男生和女生的个数。<br/>
第二行有一个整数，代表选法除以19921228的余数。
</div>

# 样例输入


<div class="pddata">
3 2<br/>
4<br/>
1 1<br/>
1 2<br/>
2 1<br/>
2 2
</div>

# 样例输出


<div class="pddata">
2 2<br/>
2
</div>

# 数据规模和约定


<div class="pdcont">
100%的数据：n ≤ 50，m, k ≤ 2500，同一对暧昧关系不会在输入中出现多次。
</div>
</div>
</div>