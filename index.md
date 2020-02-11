# 夜猫子博客
## 开发中

[夜猫群](https://qm.qq.com/cgi-bin/qm/qr?k=ECQtujv6S8rFiZw9CGjL8vwuqOMe58aw&authKey=%2BfjiVc1hQIWcKgotK%2FSfsAdF%2Bsn5fLTebVerT0hDrI8gHDRpNikH55srfbxpkx5%2B)

![bilibili](https://dss1.baidu.com/6ONXsjip0QIZ8tyhnq/it/u=2810627290,1080409091&fm=58&s=8197C732C535FA313E526557030030BB&bpow=121&bpoh=75)  

<a href="https://space.bilibili.com/296484714">
  <button>哔哩哔哩账号</button>
</a>


### 工作室室长随便做的小程序源代码

```python
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
```
