# 

 
 # 题目背景 
中中有很多照片，也很爱他的照片，不允许有任何瑕疵，但是偏偏却因为某些情况使某张照片受损了，怎么办，怎么办？于是乎想到了修照片，但是呢有些不可恢复的硬伤存在于某个照片上，怎么办，怎么办？只好把它藏起来，用它下面的照片来盖住它，还好中中只会看表面而不会去动照片，不过要是用来覆盖的照片太多他也会察觉到(因为这里照片太乱了。。)。这堆照片中的真相也许只有参与的oier知道，所以它将永远被隐藏 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;现在有一个坐标系，其左下角坐标为(0,0)，右上角坐标为(N,N)。在该坐标系中散落有M个矩形照片(xi,yi)(pi,qi)，这M个矩形照片可能相互重叠(就是说两个矩形照片间可能有相交)。现在要求用这M个矩形照片中的一个或者多个来覆盖住一个受损的照片(完全覆盖住，不然被中中发现，没准会拿出来看，到时可就over了)，这M个矩形照片不会动(没办法，动它们也许会导致中中来整理，那样那张受损的照片就可能被发现)所以对于每个照片只有两种状态(选或者不选)，求出覆盖受损照片所需要的最少的照片数，并从小到大输出方案中所用到的照片编号(若有多个可行方案，输出字典序最小的)。受损照片的大小不会超过1000*1000(毫米。。毫米。虽然有的照片太小了吧，但还是有很大滴照片),覆盖受损照片所需要的照片不会超过5个。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行两个整数：N(N&lt;=10000000)和M(M&lt;=1000)。N表示坐标系大小,就是说所有坐标都在N*N内。M表示坐标系内矩形照片数量。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行为所要覆盖受损照片的坐标,左下角(sx,sy)，右上角(ex,ey)<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下M行，每行四个数xi,yi,qi,pi,表示编号为i的矩形照片左下角坐标为(xi,yi),右上角坐标为(qi,pi)<BR>&nbsp;&nbsp;&nbsp;&nbsp;数据保证左下角坐标在右上角坐标左边(构成矩形、线段或者点),数据保证所有矩形照片不会超出坐标系，数据也保证必定有一组或多组矩形照片组合能覆盖住受损照片。<BR> 

 
 # 输出格式 
输出包括一行，第一个数为覆盖所需的最少照片数，之后为该覆盖方案所采用的矩形照片的编号从小到大输出，若有多组可行方案，输出字典序最小的(即：优先选择最小编号的，若最小编号相等则优先选择次小的，以此类推) 

 
 # 提示 
数据强大吗？不强大。<BR>数据很弱吗？不可能。<BR>样例说明:<BR>&nbsp;&nbsp;&nbsp;&nbsp;坐标系范围为(0,0)到(1000,1000)，5个可用矩形照片，受损照片坐标为(1,3)(1,4)。将受损照片覆盖所需的最少照片数为1，方案有2个,分别为使用第1个照片和使用第2个照片。方案1的字典序比方案2的小，所以输出为1&nbsp;1<BR><BR> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1000 5
1 3 1 4
1 1 9 9
1 3 100 999
77 77 88 88
1 3 1 3
1 4 1 4</td><td>1 1</td></tr></table>