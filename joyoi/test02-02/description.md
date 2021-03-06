# 题目背景
  2013年6月20日上午十时，这是一个激动人心的时刻，中国首次在神舟飞船上进行了太空授课。航天员王亚平的精彩实验演示，令人惊叹，给小Q留下了深刻的印象，作为小小天文学迷的他，更加坚定了探索科学世界的理想。
# 问题描述
  小Q平时对航天知识很感兴趣，知道了要想把航天器送上太空围绕地球飞行，那可不是一件容易的事，必须让航天器达到一定的飞行速度。
	
  天文学上有五种宇宙速度，它们是：
	
  第一宇宙速度（环绕速度）：是人造地球卫星的最小发射速度，大小为7960m/s。我国航天器天宫一号就至少要达到这个速度！
	
  第二宇宙速度（脱离速度）：是指物体完全摆脱地球引力束缚，飞离地球的所需要的最小初始速度，大小为11200m/s。
	
  第三宇宙速度（逃逸速度）：是指在地球上发射的物体摆脱太阳引力束缚，飞出太阳系所需的最小初始速度，其大小为16700m/s。
	
  第四宇宙速度，是指在地球上发射的物体摆脱银河系引力束缚，飞出银河系所需的最小初始速度，大约为115000m/s。
	
  第五宇宙速度指的是航天器从地球发射，飞出本星系群的最小速度大小，目前科学家估计2000000m/s左右的速度才能飞离。 
	
  请你判断某航天器是否达到某宇宙速度。
# 输入格式
  只有一个整数V，表示某物体的速度，单位是“m/s”。
# 输出格式
  有二个整数，之间用一个空格分隔。
	
  第一个数是输入中的速度。
	
  第二个数的意义是：如果达不到第一宇宙速度就显示0；达到第一宇宙速度就显示1，达到第二宇宙速度就显示12，达到第三宇宙速度就显示123，达到第四宇宙速度就显示1234，达到五宇宙速度就显示12345。
# 提示
* **样例解释**

 【输入输出样例1解释】

  V=1000，先输出1000；因为 V < 7960，达不到第一宇宙速度，所以再输出0。
	
 【输入输出样例2解释】

  V=116000，先输出116000；因为115000≤V< 2000000，达到第四宇宙速度，所以再输出1234。
	
* **数据范围**

  1≤V≤123456789012346。# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1000</td><td>1000 0</td></tr><tr><td>116000</td><td>116000 1234</td></tr></table>
