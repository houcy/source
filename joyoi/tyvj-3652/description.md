# 

 
 # 题目描述 
<p>
标点符号的出现晚于文字的出现，所以以前的语言都是没有标点的。现在你要处理的就是一段没有标点的文章。 

 
 # 输入格式 
<p>
输入文件第一行是两个正整数n和m，表示字典D中有n个单词，且有m段文章需要被处理。 

 
 # 输出格式 
<p>
对于输入的每一段文章，你需要输出这段文章在字典D可以被理解的最长前缀的位置。 
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
<tr><td>4 3
is
name
what
your
whatisyourname
whatisyouname
whaisyourname
</td><td>
14
6
0	整段文章’whatisyourname’都能被理解
前缀’whatis’能够被理解
没有任何前缀能够被理解

</td></tr></table>