# 

 
 # 题目描述 
<p>
问题描述：<br>　　也许你用过Microsoft Excel之类的电子制表软件，这类软件最令人称道的就是强大的公式计算功能。现在希望你也来实现一个具有最基本功能的电子制表软件。<br>　　表格共有m列(0 < m ≤ 26)，从左到右依次用A到Z的大写英文字母表示；有n行(0 < n ≤100)，从上到下依次用1到100的整数表示。这样，每一个单元格的位置就可以唯一地用它所在的列和行表示出来，例如从左到右第3列，从上到下第5行的单元格就可以用“C5”来表示（注意，这里字母和数字中间没有空格）。<br>　　现在对表格进行了一系列的操作，这些操作主要就是赋值和查询。定义操作的输入规则如下：<br>　　　1、每个操作占一行，根据操作类型的不同，每行中可能有二至四个用空格隔开的“单词”；<br>　　　2、每行的第一个单词指定了该操作涉及的单元格的位置；<br>　　　3、每行的第二个单词指定了相应的操作，可能是：input,output,sum,avg<br>　　　　(1)、如果第二个单词是input，表示接下来的一个整数是要赋予该单元格的值，这个值是不超过1000的正整数<br>　　　　(2)、如果第二个单词是output，表示你需要在输出文件中输出这个单元格当前的值<br>　　　　(3)、如果第二个单词是sum，表示接下来输入的两个单词定义了一个矩形区域，该单元格的值就应该恒为这个矩形区域中所包含的单元格的值的和，直到该单元格被重新定义<br>　　　　(4)、如果第二个单词是avg，表示接下来输入的两个单词定义了一个矩形区域，该单元格的值就应该恒为这个矩形区域中所包含的单元格的值的算术平均数，直到该单元格被重新定义；<br>　　　4、“输入的两个单词定义了一个矩形区域”是指输入一个矩形区域的左上角和右下角的单元格的位置，这样就唯一确定了这个矩形区域；<br>　　　5、所有时刻，每个单元格的值均为整数，如果不是，则向下取整；<br>　　　6、如果某个单元格的值没有在上文定义，则它的值默认为0；<br>　　　7、不会出现循环定义的情况；<br>　　　8、在操作过程中所有单元格的值不超过2^31-1。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行输入两个用空格隔开的正整数m和n，分别代表表格的列数和行数。<br>　　第二行输入一个正整数s，表示操作的总数。<br>　　以下s行每行输入一个操作，具体格式参见问题描述。<br><br></p> 

 
 # 输出格式 
<p>
　　对于输入数据的每一个“output”操作输出一行结果。因此，输出文件的行数等于输入文件中“output”操作的个数。<br><br></p> 

 
 # 提示 
<p>
数据规模：<br>　　对于30%的数据，m,n,s ≤ 10；<br>　　对于100%的数据，m ≤ 26，n ≤ 100，s ≤ 100。<br></p> 
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
<tr><td>3 5
5
A1 input 100
B2 input 200
C3 sum A1 C2
C5 avg B2 C4
C5 output

</td><td>83
</td></tr></table>
