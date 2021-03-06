# 

 
 # 题目描述 
<p>
　　出于最高安全性考虑，司令部采用了特殊的安全操作系统，该系统采用一个特殊的文件系统。在这个文件系统中所有磁盘空间都被分成了相同尺寸的N块，用整数1到N标识。每个文件占用磁盘上任意区域的一块或多块存储区，未被文件占用的存储块被认为是可是用的。如果文件存储在磁盘上自然连续的存储块中，则能被以最快的速度读出。<br>　　因为磁盘是匀速转动的，所以存取上面不同的存储块需要的时间也不同。读取磁盘开头处的存储块比读取磁盘尾处的存储块快。根据以上现象，我们事先将文件按其存取频率的大小用整数1到K标识。按文件在磁盘上的最佳存储方法，1号文件将占用1, 2, …, S1的存储块，2号文件将占用S1+1, S1+2, …， S1+S2的存储块，以此类推（Si是被第i个文件占用的存储块的个数）。为了将文件以最佳形式存储在磁盘上，需要执行存储块移动操作。一个存储块移动操作包括从磁盘上读取一个被占用的存储块至内存并将它写入其他空的存储块，然后宣称前一个存储块被释放，后一个存储块被占用。<br>　　本程序的目的是通过执行最少次数的存储块移动操作，将文件安最佳方式存储到磁盘上，注意同一个文件的存储块在移动之后其相对次序不可改变。<br></p> 

 
 # 输入格式 
<p>
　　每个磁盘说明的第一行包含两个用空格隔开的整数N和K(1≤K≤N≤100000)，接下来的K行每行说明一个文件，对第i个文件的说明是这样的：首先以整数Si开头，表示第i个文件的存储块数量，1 <= Si <= N-K，然后跟Si个整数，每个整数之间用空格隔开，表示该文件按自然顺序在磁盘上占用的存储块的标识。所有这些数都介于1和N之间，包括1和N。一个磁盘说明中所有存储块的标识都是不同的，并且该盘至少有一个空的存储块。</p> 

 
 # 输出格式 
<p>
　　对于每一个磁盘说明，只需输出M，M表示将文件按最佳方式存储到磁盘上所需进行的最少存储块移动操作次数。如果文件已按最佳方式存储，仅需输出“no”。</p> 

 
 # 提示 
<p>
【问题分析】<br>　　本题可以看作是一个置换的调整问题。按文件块的目标位置对文件块编号后，调整文件块位置的问题就转化为调整置换的问题了。不过，本题还有一点特殊之处，就是存在一些数，它们不要求归位，这些数可作为交换空间。<br>　　找出所有的循环节，分情况讨论。如果一个循环节上所有的数都是要求归位的，那么必须先利用交换空间将一个数先交换出去，然后其他数都归位，最后再把交换出去的数换回来。如果这个循环节上有不需要归位的数，则可直接贪心，将可以归位的尽量归位即可。<br><br></p> 
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
<tr><td>20 3							
4 2 3 11 12
1 7
3 18 5 10
</td><td>9</td></tr></table>
