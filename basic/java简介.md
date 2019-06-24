# 基本概念

jdk(java development kit), java语言的软件开发工具包。主要有两个组件：

- javac 编译器，将源程序转成字节码
- java 运行编译后的java程序(.class后缀的)



jre(java runtime environment)

包括java虚拟机(jvm),java核心类库和支持文件



jdk和jre的区别：

- 如果只需要运行java程序，下载并安装jre即可。
- 如果要开发java软件，需要下载jdk才可以。

所以jdk是面向开发人员的，jre是面向使用java的人员的。而且在jdk之中附带了jre的。



编译：

javac hello.java 生成hello.class字节码文件。

java hello 不用后缀，有后缀会发生错误。



# 语法

标识符：java标识符由数字，字母和下划线（_），美元符号（$）组成。在Java中是区分大小写的，而且还要求首位不能是数字。最重要的是，Java关键字（于该文章后半部分）不能当作Java标识符。

