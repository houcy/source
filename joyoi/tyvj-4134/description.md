# 

 
 # 题目背景 
<p>shlw&nbsp;love&nbsp;matrix&nbsp;-&nbsp;footoredo</p> 

 
 # 题目描述 
<p>给定数列&nbsp;{hn}&nbsp;前&nbsp;k&nbsp;项,其后每一项满足<br />
<img alt="" src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQH/2wBDAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQH/wAARCABIAKQDASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD+/iiiigAooooAKKKKACiiigAr8mPgz/wUDlj/AGk/+CiehftMfGL9m74c/sw/s2fHj4Pfs9fAn4ha0V+D15rfxN1z4OaZ8Xvi/wCBvFfijx58VfEGgeNte8EWvj74f6JHdeHNI8FsLnT/ABVqF14fhsDAbP8AWev5Yv2d/wDgnT+2P8ItY0n4xeP/ANnzwh+0B4i/bu1j9tbxn+3Z+z78eNT+A/xK+GPwS+J/xc+OmgfEz9mK/wDDcusXY1DTfhnoOgabptn+0dovwy8WfEdfF0/w3+Hkvh3wBqPiHw54V1HRAD+p2iiigAooooAKKKKACiiigAooooAKKKKACimuCysFYoxUhXADFSQQGAYFSVPOCCDjBGK/Hv8A4JCftDftDftF+HP2yvFnx1+NMXxj8G+DP25/jt+z9+zT4jn8CfD/AMAXviP4T/ASTRvB+q+MVtfAej6NZ6zF4j8ejxYsFxPHdzW1hotq3mQ/aZIEAP2GooooAKKKKACvgH/gpr+2F8Wv2C/2QviD+1V8Jf2Yrv8Aaym+FEthrvxC+Gmm/E1vhbq2j/C6OO8Pi34i2Grx/Dv4mzaxF4IK6dqWu6JD4egaHwu+u+JZdUtrbw5Pb3n39Ve8s7TULS6sL+1t76xvbeezvbK8giubS7tLmJobm1uraZXhuLe4hd4p4JUeKWJ2jkVlYggH4Lf8E+v+Crv7ZP8AwUw/Z10b9pf9mX9jf9i298G3+t6z4W1/wx4v/wCCknxd0f4g/D/xboUyC+8LeO9A0n/gmd4hsNI1l9OudM1+xWz1rU7HUfD+taRqtlfT296u37Zm+LX/AAVbijeRP2FP2GbhlGRDD/wUz+NSyyH+6huP+CXUEIP+/Ki+9fybfGbwx42/4NaP+CqOn/tE/DXR9e1T/gkN+3p4mi8P/E3wLotvd39j8F/E32i81SfRNLtIRIkfiL4WG91jxj8Io5kS68Y/Ci68afDaJ7rWfD154otf7vPBfjPwn8RfCHhb4geA/EWkeLvBHjfw9o3i3wh4q0C+g1PQ/EnhnxDp9vq2h67o+o2zyW99pmq6bd219Y3UDtFPbTxyIxVhQB+H37Tf/BRX/gsL+zN4U1TxxJ/wRA8P/HnwvodtJeaxc/s4f8FELL4keILS1jVmea1+Ht7+x14Z+Jev7QpLxeGPBut3ESZlmijhV5F/Tz9iD9rHwT+3L+yf8DP2rfAFhNomh/GTwPZeIb3wrd3w1LUfAvi+yuLrQfH/AMPNWv1s9NF5q/w/8c6T4h8Hapd/2dp4u73RJrpLK1jmSFPqqvL/AIa/Bz4ffCK8+Jd18PdDHhyL4s/EnV/i54x0u0ubg6LL4/8AEWi+H9H8T69o+ku7WOgP4pk8OWviLxJa6RDaWeteM9S8SeMb+CbxJ4n17UtQAPUKKhmuILcI1xPDAsksVvG00iRCSedxHDChdlDyzSMEijXLyOQqKWIFTUAFFfFP/BR34v8AiL9nz9hL9q347+EviPP8KPE/wZ+CXjn4n6B4ztvDfhnxdcQ6x4H0ifxFpvh+Dw94xstQ8O6hN41vdPg8FwrqFpIYJdfS5tWivIbeZOk/YS8S/Gbxf+xv+zD4n/aP8SWfif8AaE8U/Af4V+M/jPe2mjaJ4cFv4/8AG3g7S/FOu6Y3h7w/Z6dpWkrpF5qkujwxWmn2cU8enfaRCGlc0AfWVFFFABRRRQAUUUUAfMH7bH7Qdj+yh+yB+05+0rfSW6D4H/Av4nfErTobnYY9Q1/wt4R1XUvDOjKsn7uS413xFDpejWsTkJLdX0MTEK5I/lT1n9h3wN+y5/wS0/4JG/s7eEPCkQ/4KA/toftP/sZ3g+Oeo28WsfHf4V+I9d+IFn+2F+0R4j8GeO9Rjl8ReBvBPwt0fTvGOkarovhKfTdHul8Sa1qWo6PqWu+NvFOqar/W5+0f+zn8Hv2tfgt43/Z5+PvhRvHHwh+I0OiWvjTwkuueIPDia7Z6B4l0bxbp9jcat4X1TRtchs21rQNNkvra01K3j1Kzjn02+W40+8urablf2gf2QfgJ+05dfCrUviz4V1e6134I694h8Q/CvxR4M8ceOPhl4t8F3PjHwXrHw48aWOjeKfhz4i8L6/baL4w8B6/q/hbxDo66h9hvtOuYZlhh1LTtLvrIA8u8e/8ABSv9in4aax8K9D8XfGmK3u/jfo3hrWvhNNo3gT4meK9N8ejx1pnjbWPhxonhvVPCng3WtP1Lxh8U9O+HHjef4U+CYLhvFvxMk0FrLwRo2u3+q6Da6r7z8CP2jPhN+0jonjPW/hTreraj/wAK3+IeufCb4iaF4l8IeLvAXi7wJ8SPDmm6HrWr+D/FfhHxxonh7xHo2rQaH4m8Oa5At1pq21/o2u6TqlhcXVlfQTN8u/E/9iiXxz+2r+w38atG0r4Y+GPgL+x34G+O2o23gvTNNaw8R6p8ZPF/gvwR8H/gtcadoVj4fj8OQ+DvhX8J7n4u2ek3cutw6hoGp67oljoehtaGW/0zA/4Jz/spftDfsuf8NIr8cfFnww8RSfGr9o342/tAXF/8OrjX9RvPGfjH4u/FPxbry+MPE7eI/DHh2Twcnh/4O2vwX+E3h/4caHceKdN0V/h/4i1648a6/D4k0bTPC4B7b+3LqPh3TPgh9o8T+Nv2w/AOmt4w0CIa7+w78Nfid8VPjc9y0OptFYHw18JvhL8Z/FMPg+4VJJNf1WTwjDpVrPBplvd6zZTXlpb3v44/8Jh8G/8Ao57/AIOS/wDxCz9uP/6X5X9KdFAH5pf8E9dZ8GatL8VV8JfFL/gpV8R2gj8Hm/T/AIKD/BD47fCGHSRI3iQWz/Cuf4zfs8fAuHXpL0pOPGEXh2fxLJpq23ht9Vh0pb7Tn1D9LaKRmVFZ3ZURVLMzEKqqoyzMxwAoAJJJAAGTxQB8Zf8ABQn9nT9mn9qn9jb4+/Bv9rq50XRfgLrPgDXNZ8aeOdbvtP0dfhYnhaym8QWHxX0zX9TBstA1j4d3lhF4nsdUut1iPsEtnq1vfaPeahYXX5H/APBsN8EP2vPgP/wT7v8Awt+0H44Xxf8AAnUfiZ4i139h+HW/Dmv+G/H8f7O+oXt9Np/jDWtI8RSpqnhfwX8VL14/iJ8M/AOtWEfiPwtomu313qd/Np/iHRNH8P8AuMrS/wDBZP4zvaRmW4/4JP8A7OXxC23swLDRf+CjH7RHw71zmxhIIj8SfscfAnxbpgN7LmXw18evi1pC2sf9t+BPBE76r+5aIkSJHGixxxqqRxooRERAFREVQFVVUBVVQAoAAAAoAdRWbrOs6P4d0jU9f8QarpuhaDomn3mrazres31rpmkaRpenwSXV/qWp6leywWdhp9jaxS3N5eXc0VvbQRyTTSJGjMPmD9j/APa58Cftq+BPHHxh+EFo2o/BLTvi140+Gvwm+KEV/wDa9G+N+ifDv+zPDvi34l+EofsFqLfwavxRt/HvgPw5erd6nD4mtPA7eL7G6j0vX7C2hAPwR8IfFPwX+094U/4LRf8ABSf9tzwZ4f8AiJ8Jf2K/iR+1N+yx+yj8E/ibYw6x4K+GXgn9lTwWq+N/Hnhbw1qiHT9N+M/7RHxFu7XTtQ8axQH4haO2k6d4D8M67YaFHFZXX11/wTy+PPwz/Yf/AOCQP7PsX7Rn7QWuN8SvBnwetvFnxo8X+LdJ+JXx08e+F/jF8bvhdrn7b3i618XaJodvr3jfxhc/D34ceOtR+JPjGG1uni0P4a+H73xBq+raL4ftX1OD7o+If/BMD9iX4r3Xxaj+IPwhvPEnhD46+Jtf8efFv4SXPxJ+KVp8D/HXxK8UeHLXwtrnxS1v4Lab4zsvhnJ8S7zS7DTb2LxvD4Zh1/TvF2l6Z8Q9MvLL4h2Fr4qi8Z/a6/4JsaZ46/YT8afsi/szW2h6LJ478ZfDe68eaj8XfH3j/WvEvxG+Gdv41+G1p8b/AATqnxu1qy+KPxD0PWfiR8BfBEvwZ0rxDNpPimy0LwhDoXgu00fTvCum6aNEAPkL/gshLrnxu/YP/Yg/YXvPirD8UPFX/BSb9pX9kH9nnx18W/A2hWvgWTxr8KbS60343/HT40+FfCttfa9aeFtF1Dwr8N31VdCt9R1i00yy8VWmjPdX9k8074Mnhz4EfBT/AILd/BPwT8D9D8MfA74bfsnfsKeL9c/ag8W+F7D7HefFr4hftkfGv4bfCD9nD4Y/GTxJbxXniz4s/EfXPFXhW8+IHhzUPGt34g8Tap4k1t9WfWLzWvEV59q/YvSv2VfB3jLXP2UfjF+0DoPhnxn+0X+ynpnj26+HHijwi+v+GvAngLxP8XfCMXgz4hReDfBtrf2Okalolp4UX/hC/CF74w0jU9b0vQIP7QhbT9d1LUrmSzqP7FX7N+q/tGaj+1Xd+A7n/hcuu2Xw5tfFGqW/i7xlaeFfGV58Hf8AhKP+FReIPGvw6tdeh8AeLvFHwvPjTxLL4D8ReIPDeoar4bvb2w1XT7mPVvDXhS/0MA8o1n/gqF+xbo/jn4mfDCP4k+K/EXxI+Eel6z4k8beBfBfwU+OHjbxPaeC/DPiDxp4S8VfETSNM8LfDvVpPEvw08KeL/h54y8IeJviJ4dOp+DdF8W6RbeGb7Wotc8R+FLHXftH4e+P/AAb8V/APgj4o/DrxBYeLfh98SfCHhrx94F8VaU0r6Z4l8HeMNGsvEPhnX9OaaOGZrHWNF1Gy1G0M0MUpguI/Mijfcg/Ij4k/8E5/jt4g0/8A4LEeKPh54v8AhB4D+Lv7eHw28KfAT9mfV4Ydd/sL4T/BbwX8B/8AhCrSw8Vz2PheC+8M674j+Knj/wCNnjHU18I6f4osdLm1rw34jWXXNSt5dHsvrj4efsV+C/EX7MPwg+AX7THgnwV4p0r4RWtnpPgTwT4O17xZF4S+HHg/wrp83g/4Z+DNI8UWUXgTxD4yn8I/De20bQdb8Wa1ouiDxX4hj1fX7bwx4b0+70zQdJAPu+vivxX+098PdW/a5+E/7MPhH9oLRvCfxI0y8+IfiXx/8Jb34S+JvEf/AAtzQ/Cnwx0LV9T8AeHPi7cPpfgXwT4z+Hn/AAtz4RfF3xXoOnXfifxvJ4P1bw1FeaBo/h/xV/bD5/h7/gmx+xL4V1/RPFGgfAvTNP13w5q+m67ot+vjH4jXDWOraReQ3+nXawXfjCe1ma2u7eGYRXME0EhTZNFJGWQ+Ta5+x98b7j/gp5o/7Yeh658JbP4O6d+z7oXwf0ywmi1ZPiH4Nn1fx/4s+IPx8m0TwmPC1z4S1fxB8dtS0L9nrQ9Q+KN54y0zW/Dfgn4e+JfD1v4UvtR1HSfEMYB+ntFFFABRRRQAUUUUAFFFFABXyP8Atyfsv69+2X+zT8Q/2bNG+PPxF/ZzsPilZJ4d8YfEL4U2mhTeOLjwPdCWPxL4Q0y91+1u4NHtPFtm40jW9RsY01J9Dm1HTLaeBNRmlX64ri/iN480T4X+AvGHxF8Rw6xdaH4K8O6t4k1Kx8O6PfeIfEepQaVZy3f9l+HfD+mRTalr/iHVHjTT9D0PToZr/V9VubTT7OKS5uY0IB+CvgX/AIIcftGfDHwX4V+HPw7/AOC2H/BQ7wT4D8DeH9J8K+DvCHhiD4NaP4e8M+G9CsodO0fRNF0qy8Fw2lhpunWNvDa2lrbxJHFFGqqOM100/wDwRs/a8uInhk/4Ls/8FMFSRSrGDU/hXbSgHuk9t4Tinib0aORGHYivrz9n39tL4fa78Gvi9+0fo+hftqfErStf/aw+Knws1j4Y3Pw0tPjZ4v8AhR44+E903wl8YeDfhnov7PNj4t0Kf4HaP4g+GWq6nZeLtP8AFPjjSrrxZ4j1p7zxlPqWrR6TY9p/w8X8D/8ARrv/AAUI/wDEFv2iP/mMoA/GL46/8Gx2uftO6M/hr9of/gsX/wAFMPjR4Vkkjmbwh8R/iPpvirwd58MnmxXA8I6r9o8NrcRyYdLhdLWZSkeHxGgX+ij9lf8AZy+H/wCyH+zh8E/2YvhZDcR+Avgb8OPC/wAOvD9xerbrqerxeHtNhtb7xJrZtIre1l8QeKdUF94j8Q3FvBBDda3qt/cxwxLKEX87v+CvHxL+N3w2/Zb+HX7QnwP+PPxd+C0kXx5/Yy8Lar8P9I8NfD3Sbbxf4f8AjJ+1R8FvBniKw8fP41+G+s/FPw1qEHhPxPqukXOi+E/F/gaWOee4sPEltqVuLzTpv2OoAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAqhqtpPqGmajYWuo3ekXN9YXlpb6tYLbPfaXPc28kMOo2aXsF1Ztd2Ujrc263drc2zTRIJ4Joi8bFFAH5g/sr/wDBMq2+BH7Ivgv9k3x9+0V8ZPGGj+A7jw/JoPi34HeO/i1+yXq0f9iabqn9s6leXvwp+Llx4y1TX/ih428T+N/in8WrzWPHWpaZ4u8c+KY5k0bT9M8KeE7LS/Rf+HbXwg/6L1/wUI/8WS/tzf8Az+aKKAMP/goB+xD8Wv2xfgh4K/Z9+HH7Qfgn4M+BPDfjH4MeO9a1X4jfBTxz+0P4/wDEHiD4B/E/wJ8VPAHleL5P2k/hNJDaXuteA7Kz8c3HiXT/ABl4j8U2l9eXNv4i0TVXbUJPvrwRaeN7Dwpodn8SPEHhXxX45t7MR+JPEXgjwfq/w/8ACmrah5shN1ofg3XvHPxL1jw9ZmExILC/8d+Jp1lSSU6kySrDEUUAdVRRRQAUUUUAFFFFABRRRQAUUUUAf//Z" style="width: 164px; height: 72px;" /><br />
其中&nbsp;a1&nbsp;,&nbsp;a2&nbsp;,&nbsp;.&nbsp;.&nbsp;.&nbsp;,&nbsp;ak&nbsp;为给定数列。请计算&nbsp;h(n)&nbsp;,并将结果对&nbsp;1000000007&nbsp;取模输出。</p> 

 
 # 输入格式 
<p>第&nbsp;1&nbsp;行包含两个整数&nbsp;n,&nbsp;k&nbsp;第&nbsp;2&nbsp;行包含&nbsp;k&nbsp;个整数&nbsp;h1&nbsp;,&nbsp;h2&nbsp;,&nbsp;.&nbsp;.&nbsp;.&nbsp;,&nbsp;hk<br />
第&nbsp;3&nbsp;行包含&nbsp;k&nbsp;个整数&nbsp;a1&nbsp;,&nbsp;a2&nbsp;,&nbsp;.&nbsp;.&nbsp;.&nbsp;,&nbsp;ak&nbsp;。</p> 

 
 # 输出格式 
<p>一行一个整数&nbsp;h(n)&nbsp;mod&nbsp;1000000007。</p> 

 
 # 提示 
<p>对于&nbsp;10%&nbsp;数据,满足&nbsp;n&nbsp;&le;&nbsp;1000,&nbsp;k&nbsp;&le;&nbsp;100;<br />
对于&nbsp;30%&nbsp;数据,满足&nbsp;n&nbsp;&le;&nbsp;10^9&nbsp;,&nbsp;k&nbsp;&le;&nbsp;100;<br />
对于&nbsp;100%&nbsp;数据,满足&nbsp;n&nbsp;&le;&nbsp;10^9&nbsp;,&nbsp;k&nbsp;&le;&nbsp;1000,&nbsp;|h&nbsp;i&nbsp;|&nbsp;&le;&nbsp;10^9&nbsp;,&nbsp;|a&nbsp;i&nbsp;|&nbsp;&le;&nbsp;10^9&nbsp;。</p> 
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
<tr><td>6 4
3 -1 0 4
-2 3 1 5</td><td>73</td></tr></table>