# 题目描述


<div>
	【问题描述】
</div>
<div>
	 
</div>
<div>
	在大型工程的施工前，我们把整个工程划分为若干个子工程，并把这些子工程编号为1、2、……、N；这样划分之后，子工程之间就会有一些依赖关系，即一些子工程必须在某些子工程完成之后才能施工。由于子工程之间有相互依赖关系，因此有两个任务需要我们去完成：首先，我们需要计算整个工程最少的完成时间；同时，由于一些不可预测的客观因素会使某些子工程延期，因此我们必须知道哪些子工程的延期会影响整个工程的延期，我们把有这种特征的子工程称为关键子工程，因此第二个任务就是找出所有的关键子工程，以便集中精力管理好这些子工程，尽量避免这些子工程延期，达到用最快的速度完成整个工程。为了便于编程，现在我们假设： <br/>
（1）根据预算，每一个子工程都有一个完成时间。 <br/>
（2）子工程之间的依赖关系是：部分子工程必须在一些子工程完成之后才开工。 <br/>
（3）只要满足子工程间的依赖关系，在任何时刻可以有任何多个子工程同时在施工，也既同时施工的子工程个数不受限制。 <br/>
（4）整个工程的完成是指：所有子工程的完成。 <br/>
例如，有五个子工程的工程规划表：
</div>
<div>
	 
</div>
<div>
	<img src="/upload/image/20120925/20120925164751_92561.jpg" alt=""/><br/>
 
</div>
<div>
	其中，表格中第 I+1 行 J+2 列的值如为 0 表示“子工程 I”可以在“子工程 J”没完成前施工，为 1 表示“子工程 I”必须在“子工程 J”完成后才能施工。上述工程最快完成时间为 14 天，其中子工程1、3、4、5为关键子工程。 <br/>
<br/>
    又例如，有五个子工程的工程规划表：
</div>
<div>
	 
</div>
<div>
	<img src="/upload/image/20120925/20120925164817_39594.jpg" alt=""/> 
</div>
<div>
	 
</div>
<div>
	上述的子工程划分不合理，因为无法安排子工程1，3，4的施工。
</div>
<div>
	 
</div>
<div>
	【输入格式】
</div>
<div>
	 
</div>
<div>
	第1 行为N，N是子工程的总个数，N≤200。 <br/>
    第 2 行为N个正整数，分别代表子工程1、2、……、N的完成时间。 <br/>
    第 3 行到 N+2 行，每行有 N-1 个 0 或 1。其中的第 I+2 行的这些 0，1，分别表示“子工程 I”与子工程1、2、…、I-1、I+1、…N的依赖关系，（I=1、2、……、N）。每行数据之间均用一个空格分开。 <br/>
 
</div>
<div>
	【输出格式】
</div>
<div>
	 
</div>
<div>
	如子工程划分不合理，则输出-1； <br/>
    如子工程划分合理，则用两行输出：第1行为整个工程最少的完成时间。第2行为按由小到大顺序输出所有关键子工程的编号。 <br/>
 
</div>
<div>
	【输入输出样例】
</div>
<div>
	 
</div>
<div>
	输入文件名：project.in <br/>
5 <br/>
5 4 12 7 2 <br/>
0 0 0 0 <br/>
0 0 0 0 <br/>
0 0 0 0 <br/>
1 1 0 0 <br/>
1 1 1 1
</div>
<div>
	输出文件名：project.out <br/>
14 <br/>
1 3 4 5
</div>
