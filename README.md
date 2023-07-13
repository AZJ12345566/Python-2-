# Python-2-
Python学习笔记(2)
# p10 变量的定义和使用
name='马利亚'
print(name)
#变量由三部分组成：
#1.标识  2.类型  3.值
print('标识',id(name))
print('类型',type(name))
print('值',name)

# 以下为内存分析图
#id 23291470
#type str
#value 马利亚

# p11 变量的多次赋值
#多次赋值后，变量名会指向新的内存空间
#变量名经过多次赋值后，原来的内存空间称为内存垃圾

# p12 Python中常见的数据类型
#常见的数据类型
#1.整数类型->int->98
#2.浮点数类型->f;oat->3.14159
#3.布尔类型->bool->True,False
#4.字符串类型->str->‘人生苦短’
