## 廖雪峰java教程笔记

### 前言

之前的一版java教程笔记可能不够实用，对于初学者或者高手而言，重新复习或者体会新的知识，能让自己的内心更加充实。

下面一段时间，我将不定期更新重新学习过程中遇到的问题，以及从其中得到的感悟。


如果您有兴趣，可以通过邮箱方式联系在下，阁下的贡献也是提升自己的好方法，不是吗？

## idea 配置JAVA版本

![idea 2020.1设置 java 14](img/ideaSetting.png)


# 快速入门

## JAVA 程序基础

- [基本结构](BasicStruct.java)
- [变量](VariableAndDataType.java)
  - [整型例子](IntDemo.java)
  - [浮点型例子](IntDemo.java)
  - [布尔型例子](BooleanDemo.java)
  - [字符例子](CharDemo.java)
  - [常量例子](ConstDemo.java)
  - [var关键字例子](VarDemo.java)
  - [变量作用域例子](VariableScope.java)
- [整数运算-四则运算](IntegerArithmeticDemo1.java)
  - [整数运算-溢出](IntegerArithmeticDemo2.java)
  - [整数运算-自增自减](IntegerArithmeticDemo3.java)
  - [整数运算-移位运算左移](IntegerArithmeticDemo4.java)
  - [整数运算-移位运算右移](IntegerArithmeticDemo5.java)
  - [整数运算-移位运算右移-负数](IntegerArithmeticDemo6.java)
  - [整数运算-移位运算右移-无符号](IntegerArithmeticDemo7.java)
- [浮点数运算](FloatingPointArithmeticDemo1.java)
  - [浮点运算-比较大小](FloatingPointArithmeticDemo2.java)
  - [浮点运算-类型提升](FloatingPointArithmeticDemo3.java)
  - [浮点运算-溢出](FloatingPointArithmeticDemo4.java)
  - [浮点运算-强制转换](FloatingPointArithmeticDemo5.java)
  - [浮点运算-四舍五入](FloatingPointArithmeticDemo6.java)
 - [布尔运算](BooleanArithmeticDemo1.java)
   - [布尔运算-三元运算符](BooleanArithmeticDemo2.java)
 - [字符和字符串](CharAndStringDemo1.java) 
   - [字符和字符串-字符类型](CharAndStringDemo2.java) 
   - [字符和字符串-字符串类型](CharAndStringDemo3.java) 
   - [字符和字符串-字符串连接](CharAndStringDemo4.java) 
   - [字符和字符串-多行字符串](CharAndStringDemo5.java) 
   - [字符和字符串-字符串不可变特性](CharAndStringDemo6.java) 
   - [字符和字符串-空值null](CharAndStringDemo7.java) 
 - [数组类型](ArrayArithmeticDemo1.java)  
   - [字符串数组](ArrayArithmeticDemo2.java)
   - [字符串数组引用示例](ArrayArithmeticDemo3.java)
   
## 流程控制

- [输入和输出](StdinAndStdoutDemo1.java)
  - [输入和输出-格式化输出](StdinAndStdoutDemo2.java)
  - [输入和输出-输入](StdinAndStdoutDemo3.java)
  
- [if判断](IfJudgmentDemo1.java) 
  - [else](IfJudgmentDemo2.java) 
  - [if ... else if ...](IfJudgmentDemo3.java) 
  - [if条件顺序](IfJudgmentDemo4.java) 
  - [判断引用相等](IfJudgmentDemo5.java) 
  
- [switch 多重选择](SwitchCaseDemo1.java)  
  - [switch 多重选择- 多个case执行同一句块](SwitchCaseDemo2.java)  
  - [语句赋值](SwitchCaseDemo3.java)  
  - [yield](SwitchCaseDemo4.java)  
  
- [while循环](WhileLoopDemo1.java)  
- [do...while循环](DoWhileLoopDemo1.java)  
- [for循环](ForLoopDemo1.java)  
  - [for循环-数组求和](ForLoopDemo2.java)  
  - [for循环-访问指定索引](ForLoopDemo3.java)  
  - [for循环-灵活使用](ForLoopDemo4.java)  
  - [for循环- for each](ForLoopDemo5.java)  
  - [for循环- break , continue](ForLoopDemo6.java)  
  - [for循环- continue](ForLoopDemo7.java)  
  
## 数组操作

- [遍历数组](ForEachArrayDemo1.java)  
  - [遍历数组- 打印数组内容](ForEachArrayDemo2.java)  
  - [遍历数组- 数组排序](ForEachArrayDemo3.java)  
  - [遍历数组- 自带排序-升序](ForEachArrayDemo4.java)  
  - [遍历数组- 自带排序-降序](ForEachArrayDemo5.java)  
  - [遍历数组- 自带排序-降序-使用Comparator](ForEachArrayDemo6.java)
  
- [多维数组](MultidimensionalArraysDemo1.java)    
  - [多维数组-获取二维数组个项](MultidimensionalArraysDemo2.java)    
  - [多维数组-打印二维数组](MultidimensionalArraysDemo3.java)    
  - [多维数组-三维数组](MultidimensionalArraysDemo4.java)  
  - [多维数组-练习](MultidimensionalArraysDemo5.java)  
  
- [命令行参数](CommandLineDemo1.java)  
  - [命令行参数-命令行传参](CommandLineDemo2.java)  
  

# 面向对象编程

## 面向对象基础
- [类](ClassBasicDemo1.java)
  - [练习](ClassBasicDemo2.java)
- [方法](ClassMethodDemo1.java)
  - [方法-this变量](ClassMethodDemo2.java)
  - [方法-参数](ClassMethodDemo3.java)
  - [方法-可变参数](ClassMethodDemo4.java)
  - [方法-传递引用参数](ClassMethodDemo5.java)
- [构造方法](ConstructMethodDemo1.java)
  - [构造方法-初始化和构造函数初始化](ConstructMethodDemo2.java)
  - [多构造方法](ConstructMethodDemo3.java)
- [方法重载](MethodReloadDemo1.java)
- [继承]()
- [多态]()
- [抽象类]()
- [抽象类]()
- [接口]()
- [静态字段和静态方法]()
- [包]()
- [作用域]()
- [classpath 和 jar]()
- [模块]()

## Java核心类


# 异常处理
# 反射
# 注解
# 泛型
# 集合
# IO
# 日期与时间
# 单元测试
# 正则表达式
# 加密与安全
# 多线程
# Maven 基础
# 网络编程
# XML 与 JSON
# JDBC 编程
# 函数式编程
# 设计模式
# Web 开发
# Spring 开发  



# 引用版权声明

【廖雪峰java教程笔记】引用内容版权归[廖雪峰的官方网站](https://www.liaoxuefeng.com)所有