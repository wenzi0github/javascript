##什么是运算符？

用表达式 4 + 5 能很快得到 4 和 5 这两个数的和为 9 。这里 4 和 5 被称为运算数，+ 叫做运算符。JaScript 语言支持以下类型的运算符：
  
•	算术运算符  
•	比较运算符  
•	逻辑（或关系)运算符  
•	赋值运算符  
•	条件（或三元）运算符
  
让我们依次看一下这些运算符。  
##算数运算符：  
JavaScript语言支持以下算术运算符：  

给定 **A=10，B=20**，下面的表格解释了这些算术运算符：  
<table>
<tr><th>运算符</th>	<th>描述</th>	<th>例子</th></tr>
<tr><td>+</td><td>两个运算数相加</td><td>A + B = 30</td></tr>
<tr><td>-</td><td>第一个运算数减去第二个运算数</td><td>A - B = -10</td></tr>
<tr><td>*</td><td>运算数相乘	</td><td>A * B = 200</td></tr>
<tr><td>/</td><td>分子除以分母</td><td>B / A = 2</td></tr>
<tr><td>%</td><td>模数运算符，整除后的余数</td><td>B % A = 0</td></tr>
<tr><td>++</td><td>增量运算符，整数值逐次加1</td><td>A++ = 11</td></tr>
<tr><td>--</td><td>减量运算符，整数值逐次减1</td><td>A-- = 9</td> </tr> 
</table>
**注意** : + 运算符不仅可以用于数字相加，还可以用于把文本值或字符串变量加起来（连接起来）。例如，"a" + 10 = “a10”。  

为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)   
##比较运算符 　
JavaScript语言支持以下比较运算符：  

给定 **A=10，B=20**，下面的表格解释了这些比较运算符：
<table>
<tr><th>运算符</th><th>描述</th><th>例子</th></tr>
<tr><td>==</td>	<td>检查两个运算数的值是否相等，如果是，则结果为true</td>	<td>A == B 为false</td></tr>
<tr><td>!=</td>	<td>检查两个运算数的值是否相等，如果不相等，则结果为true	</td><td>A != B 为true</td></tr>
<tr><td>></td>	<td>检查左边运算数是否大于右边运算数，如果是，则结果为true	</td><td>A > B 为false</td></tr>
<tr><td><	</td><td>检查左边运算数是否小于右边运算数，如果是，则结果为true</td><td>	A < B 为true</td></tr>
<tr><td>>=</td>	<td>检查左边运算数是否大于或者等于右边运算数，如果是，则结果为true</td>	<td>A >= B 为false</td></tr>
<tr><td><=</td><td>	检查左边运算数是否小于或者等于运算数，如果是，则结果为true</td>	<td>A <= B 为true</td></tr>
</table>
为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)  
##逻辑运算符：
JavaScript语言支持以下逻辑运算符：  

给定 **A=10，B=20**，下面的表格解释了这些逻辑运算符：
<table>
<tr><th>运算符</th>	<th>描述</th>	<th>例子</th></tr>
<tr><td>&&	</td><td>称为逻辑与运算符。如果两个运算数都非零，则结果为true。</td><td>	A && B 为true</td></tr>
<tr><td>||	</td><td>称为逻辑或运算符。如果两个运算数中任何一个非零，则结果为true。</td><td>	A || B 为 true</td></tr>
<tr><td>!	</td><td>称为逻辑非运算符。用于改变运算数的逻辑状态。如果逻辑状态为true，则通过逻辑非运算符可以使逻辑状态变为false	</td><td>!(A && B) 为false</td></tr>  
</table>
为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)  

##按位运算符：
JavaScript语言支持以下逻辑运算符：  

给定 **A=2，B=3**，下面的表格解释了这些逻辑运算符
<table class="dataintable">
<tr><th>运算符</th><th>描述</th>	<th>例子</th></tr>
<tr><td>&	</td><td>称为按位与运算符。它对整型参数的每一个二进制位进行布尔与操作。</td><td>	A & B = 2 .</td></tr>
<tr><td>|	</td><td>称为按位或运算符。它对整型参数的每一个二进制位进行布尔或操作。</td><td>	A | B = 3.</td></tr>
<tr><td>^</td>	<td>称为按位异或运算符。它对整型参数的每一个二进制位进行布尔异或操作。异或运算是指第一个参数或者第二个参数为true，并且不包括两个参数都为true的情况，则结果为true。</td><td>	(A ^ B) = 1.</td></tr>
<tr><td>~</td>	<td>称为按位非运算符。它是一个单运算符，对运算数的所有二进制位进行取反操作。</td><td>	~B = -4 .</td>
</tr>
<tr><td><<	</td><td>称为按位左移运算符。它把第一个运算数的所有二进制位向左移动第二个运算数指定的位数，而新的二进制位补0。将一个数向左移动一个二进制位相当于将该数乘以2，向左移动两个二进制位相当于将该数乘以4，以此类推。</td>	<td>A << 1 = 4.</td></tr>
<tr><td>>></td><td>	称为按位右移运算符。它把第一个运算数的所有二进制位向右移动第二个运算数指定的位数。为了保持运算结果的符号不变，左边二进制位补0或1取决于原参数的符号位。如果第一个运算数是正的，运算结果最高位补0；如果第一个运算数是负的，运算结果最高位补1。将一个数向右移动一位相当于将该数乘以2，向右移动两位相当于将该数乘以4，以此类推。</td>	<td>A >> 1 = 1.</td></tr>
<tr><td>>>>	</td><td>称为0补最高位无符号右移运算符。这个运算符与>>运算符相像，除了位移后左边总是补0.	</td><td>A >>> = 1.</td> </tr> 
</table>  
为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)   
 
##赋值运算符：
JavaScript语言支持以下赋值运算符：  
<table>
<tr><th>运算符</th>	<th>描述</th><th>	例子</th></tr>
<tr><td>=	</td><td>简单赋值运算符，将右边运算数的值赋给左边运算数</td>	<td>C = A + B 将A+B的值赋给C</td></tr>
<tr><td>+=	</td><td>加等赋值运算符，将右边运算符与左边运算符相加并将运算结果赋给左边运算数</td><td>	C += A 相当于 C = C + A</td></tr>
<tr><td>-=	</td><td>减等赋值运算符，将左边运算数减去右边运算数并将运算结果赋给左边运算数	</td><td>C -= A 相当于C = C - A</td></tr>
<tr><td>*=	</td><td>乘等赋值运算符，将右边运算数乘以左边运算数并将运算结果赋给左边运算数</td><td>	C *= A 相当于C = C * A</td></tr>
<tr><td>/=	</td> <td>除等赋值运算符， 将左边运算数除以右边运算数并将运算结果赋值给左边运算数</td><td>	C /= A 相当于 C = C / A</td></tr>
<tr><td>%=	</td><td>模等赋值运算符，用两个运算数做取模运算并将运算结果赋值给左边运算数	</td><td>C %= A 相当于 C = C % A </td></tr>
</table>
**注意：**同样的逻辑可以应用到位运算符，因此就有<<= , >>= , >>>= , &= , |= 以及 ^=　。   

为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)  
#其他运算符
##条件运算符（？：）
有一种运算符叫条件运算符。首先判断一个表达式是真或假，然后根据判断结果执行两个给定指令中的一个。条件运算符语法如下：  
<table>
<tr><th>运算符</th>	<th>描述	</th><th>例子</th></tr>
<tr><td>? :	</td><td>条件表达式</td><td>	如果条件为真 ? X值 : Y值 </td> </tr>
</table>
为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)  
##*typeof*运算符
*typeof*是一个置于单个参数之前的一元运算符，这个参数可以是任何类型的。它的值是一个表示运算数的类型的字符串。  

*typeof*运算符可以判断“数值”，“字符串”，“布尔”类型，看运算数是一个数字，字符串还是布尔值，并且根据判断结果返回true或者false。  

下表是*typeof*运算符的返回值：  
<table>
<tr><th>类型	</th><th>Typeof返回字符串</th></tr>
<tr><td>数值	</td><td>"number"</td></tr>
<tr><td>字符串</td>	<td>"string"</td></tr>
<tr><td>布尔	</td><td>"boolean"</td></tr>
<tr><td>对象	</td><td>"object"</td></tr>
<tr><td>函数	</td><td>"function"</td></tr>
<tr><td>未定义</td><td>	"undefined"</td></tr>
<tr><td>空	</td><td>"object" </td></tr> 
</table>
为了更好的理解此处内容，你可以自己[尝试一下](http://www.tutorialspoint.com/cgi-bin/practice.cgi?file=javascript_32)  





