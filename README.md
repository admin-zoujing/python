# python笔记

##面向过程：以指令为中心。 面向对象：以数据为中心。

# python内建数据序列

#列表   ['0','1']   可变序列

#元组   ('0','1')   不可变序列

#字符串  a          

#Unicode字符串

#buffer对象

#xrange对象

# python的关键要素
#1、基本数据类型： 数值型(整型【不可变类型】、布尔)；浮点型(浮点、复数)；字符型【不可变类型】

#2、对象引用：变量名没有类型(字母数字下划线，不能数字开头，区分大小写，禁止使用保留字)

#3、组合数据类型：序列类型(列表，元组，字符串)；集合类型(集合)；映射类型(字典)；自定义类型(类)

#4、逻辑操作符：身份操作符(is、none)；比较操作符(<、>、<=、>=、!=、==)；成员操作符(in、not in)；逻辑运算符(and、or、not)

#5、控制流语句：if；while；for；try

#6、算术操作符：+ =；- =；

#7、输入、输出：input() raw_input()  python2:print 语句   python3:print()函数

#字典(键值):  d={'x':1,'y':2,'z':3}   print "The float is %(x)f." %d

#8、函数的创建与调用

#定义函数 def printName(name) #print name

#调用函数 printName('Tony')

#判断调用 callable()

#内置函数 _builtin_

#内置函数 dir(),id(),str(),help(),len(),callable(),
