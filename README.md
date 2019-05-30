# python笔记

##面向过程：以指令为中心，由指令处理数据。 面向对象：以数据为中心，所有的处理代码都围绕数据展开。

# python内建数据序列

#列表   ['0','1']   可变序列

#元组   ('0','1')   不可变序列

#字符串  a          

#Unicode字符串

#buffer对象

#xrange对象

# python的关键要素
#1、基本数据类型： 数值型(整型【不可变类型】、布尔)；浮点型(浮点、复数、十进制数字)；字符串('a'，'b')【不可变类型】

#2、对象引用：变量名没有类型(字母数字下划线，不能数字开头，区分大小写，禁止使用保留字)  【对象：身份、类型、值】

#3、组合数据类型：序列类型(list，tuple，str)；集合类型(set,frozenset)；映射类型(dict)；自定义类型(class)

#4、逻辑操作符：身份操作符(is、none)；比较操作符(<、>、<=、>=、!=、==)；成员操作符(in、not in)；逻辑运算符(and、or、not)

#5、控制流语句：if；while；for...in；try

#6、算术操作符：+ =；- =；

#7、输入、输出：input() raw_input()  python2:print 语句   python3:print(函数)

#字典(键值):  d={'x':1,'y':2,'z':3}   print "The float is %(x)f." %d

#8、函数的创建与调用

#定义函数 def printName(name) #print name

#调用函数 printName('Tony')

#判断调用 callable()

#内置函数 _builtin_

#内置函数 dir(),id(),str(),help(),len(),callable(),

# python语句和语法
#注释：#   续行：\ '''

#代码组：缩进相同的一组语句构成一个代码块；行首以关键字开始，以冒号结束；用缩进分隔代码组

#同一行放置多个语句，以分号为分隔符

#模块：每一个脚本文件都可以被当成一个模块；模块代码可以是执行的脚本，也可以是类似库函数的代码导入

#标识符：第一个字符只能字母或下划线；区分大小写；余下字符可以是字母，下划线，数字

#注释、文档、缩进、标识符名称、python风格指南、命名惯例、

# python文件结构
#起始行: #/usr/bin/env python

#模块文档: "This is a test module"

#模块导入：import sys

#（全局）变量定义：debug=True

#类定义: class FooClass(object): "Foo class" pass    数据和方法（数据：变量，方法：函数）

#函数定义: def test(): "test function" foo=FooClass()      if debug: print 'ran test()'

#主程序： _name_导入就是模块名，执行就是_main_

# python核心数据类型
#数字：int，long，float，complex，bool

#字符：str，unicode

#列表：list

#字典：dict

#元组：tuple

#文件：file

#其他：集合（set），frozenset，类类型，None

#其他文件类工具：pipes，fifos，sockets

#类型转换：str(),repr(),format()将非字符型数据转为字符；int()转为整数；float()转为浮点；list(s)转为列表；tuples(s)转为元组；set(s)转为集合；frozenset(s)将字串s转换为不可变集合；dict(d)创建字典；chr(x):将整数转为字符；ord(x):将字符转换为整数;hex(x):将整数转换为16进制字符；bin(xx);oct(x);

#数字类型：
#python的数字字面量：布尔型（true：1 false：0），整数，浮点型，复数

#序列类型
#字符类型：字符串字面量：把文本放入单引号、双引号、三引号
#如果要使用unicode编码，则在字符之前使用u标识；文档字符串可以用_doc_属性引用

#运算符：索引[i]
        切片[i:j]
        扩展[i:j:stride]
        min(s) max(s) sum(s) all(s) any(s)



