# 1、什么是JVM？

​		JVM是Java Virtual Machine（Java[虚拟机）的缩写，JVM是一种用于计算设备的规范，它是一个虚构出来的计算机，是通过在实际的计算机上仿真模拟各种计算机功能来实现的。

​		Java语言的一个非常重要的特点就是与平台的无关性。而使用Java虚拟机是实现这一特点的关键。一般的高级语言如果要在不同的平台上运行，至少需要编译成不同的目标代码。而引入Java语言虚拟机后，Java语言在不同平台上运行时不需要重新编译。Java语言使用Java虚拟机屏蔽了与具体平台相关的信息，使得Java语言编译程序只需生成在Java虚拟机上运行的目标代码（字节码），就可以在多种平台上不加修改地运行。Java虚拟机在执行字节码时，把字节码解释成具体平台上的机器指令执行。这就是Java的能够“一次编译，到处运行”的原因。

​		优势：

​				编译后运行，跨平台，对环境无要求只要安装java环境即可运行

# 2、JVM有哪些？

​		Java的虚拟机其实是分了很多种类型的

​		Sun公司的Classic/Exact，世界第一款商用虚拟机

​		Sun公司的HotSpot，Sunjdk和OpenJdk自带使用最为广泛的虚拟机 

​		Sun公司的Mobile-Embedded VM/Meta-Circular，桌面领域虚拟机

​		BEA公司的 JRockit，曾经号称“世界上速度最快的Java虚拟机”，但是其他公司也这么说

​		IBM公司的J9，并不是公司唯一的Java虚拟机，不过是目前其主力发展的Java虚拟机

​		等等，还有很多其他的公司也研发了不同的虚拟机

# 3、JVM的结构图



