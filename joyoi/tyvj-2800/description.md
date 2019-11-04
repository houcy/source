# 

 
 # 题目描述 
<p>
写电子邮件是有趣的，但不幸的是经常写不好看，主要是因为所有的行不一样长，你的上司想要发排版精美的电子邮件，你的任务是为他编写一个电子邮件排版程序。

 
 # 输入格式 
<p>
输入文件第一行是一个整数N，表示该段要求达到的宽度，1<=N<=80。该段文章由一个或多个单词组成，单词由ASCII码值为33到126（包含33和126）的字符组成，单词与单词之间用空格隔开（可能超过一个）。单词长度不会超过段落要求达到的宽度。一段文字所有单词的总长度不会超过10000个字符，任何一行都不会超过100个字符，任何一个单词都在同一行内。</p> 

 
 # 输出格式 
<p>
对于每个段落，找出使其难看程度最小的排版形式并输出句子：

 
 # 提示 
<p>
样例解释:
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
<tr><td>28	
This is the example you  are
actually considering.
</td><td>Minimal badness is 12.</td></tr></table>