##说好听叫自己动手实现数学语言,DSL style!~
##其实就是一个计算器而已啊混蛋!

###主要任务:
1. 基础数据结构:（最近时间紧，基础结构还是直接用C++的stl吧= =）
	- 列表
	- 栈
	- 散列表
2. 词法分析(Lexer)
3. 语法分析,两种实现思路:
	- 双栈,转中缀到后缀,再计算后缀表达式.
	- 建立语法树
4. 扩展:
	- 支持变量
	- 支持绘制函数图形
	- 等等
