# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>


 
 # 输出格式 
<p>

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
<tr><td>

7 3
7
6
7
2
1
4
2

INPUT DETAILS:

The line has 7 cows with 3 features; the table below summarizes the
correspondence:
              Feature 3:   1   1   1   0   0   1   0
              Feature 2:   1   1   1   1   0   0   1
              Feature 1:   1   0   1   0   1   0   0
              Key:         7   6   7   2   1   4   2
              Cow #:       1   2   3   4   5   6   7</td><td>
4

OUTPUT DETAILS:

In the range from cow #3 to cow #6 (of size 4), each feature appears
in exactly 2 cows in this range:
              Feature 3:     1   0   0   1  -> two total
              Feature 2:     1   1   0   0  -> two total
              Feature 1:     1   0   1   0  -> two total
              Key:           7   2   1   4 
              Cow #:         3   4   5   6 </td></tr></table>