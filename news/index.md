# 鸡黍的博客——分页
### 开发中

<a href="..">
  <button type="button" class="btn"  style="background-color: #87CEFA; width: 75px;height: 50px;color: #FFFFFF">总页</button>
</a>

<details>
	<summary>鸡黍随便做的小程序源代码 展开查看</summary>
	<pre><code>
	# This Python file uses the following encoding:utf-8
	def main():
		import os
		while True:
			first = input('>>>')
			maths = raw_input('+ , - , * or / ?>>>')
			second = input('>>>')
			def plus():
				result = first + second
				print result
				next = raw_input('按任意键+回车继续>>>')
				result = 0
				os.system('cls')
			def minus():
				result = first - second
				print result
				next = raw_input('按任意键+回车继续>>>')
				result = 0
				os.system('cls')
			def times():
				result = first * second
				print result
				next = raw_input('按任意键+回车继续>>>')
				result = 0
				os.system('cls')
			def divid():
				result = first / second
				print result
				next = raw_input('按任意键+回车继续>>>')
				result = 0
				os.system('cls')	
			if maths == '+':
				plus()
			elif maths == '-':
				minus()
			elif maths == '*':
				times()
			elif maths == '/':
				divid()
			else:
				print 'Error!'
	if __name__ == '__main__':
		main()
	</code></pre>
<details>
