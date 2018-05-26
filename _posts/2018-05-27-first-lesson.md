---
layout: post
title:  "Java教程第一篇之认识计算机"
date:   2018-05-27 07:50:39
categories: Java
---
###1了解计算机基础知识之计算机概述
* A:什么是计算机?计算机在生活中的应用举例
	* 计算机（Computer）全称：电子计算机，俗称电脑。是一种能够按照程序运行，自动、高速处理海量数据的现代化智能电子设备。由硬件和软件所组成，没有安装任何软件的计算机称为裸机。常见的形式有台式计算机、笔记本计算机、大型计算机等。
	* 应用举例
		* 1：科学计算
		* 2、数据处理
		* 3、自动控制
		* 4、计算机辅助设计
		* 5、人工智能
		* 6、多媒体应用
		* 7、计算机网络
		* ... 
* B:什么是硬件?硬件举例
	* 计算机硬件（Computer Hardware）是指计算机系统中由电子，机械和光电元件等组成的各种物理装置的总称。这些物理装置按系统结构的要求构成一个有机整体为计算机软件运行提供物质基础。
	* 冯.诺依曼体系结构
	* 计算机的硬件分成5大组成部件：运算器、控制器、存储器、输入设备和输出设备。
	
		* 运算器和控制器是计算机的核心，合称中央处理单元（Central Processing Unit，CPU）或处理器.CPU的内部还有一些高速存储单元，被称为寄存器。其中运算器执行所有的算术和逻辑运算;控制器负责把指令逐条从存储器中取出，经译码后向计算机发出各种控制命令;而寄存器为处理单元提供操作所需要的数据。		*存储器是计算机的记忆部分，用来存放程序和程序中涉及的数据。它分为内部存储器和外部存储器。内部存储器用于存放正在执行的程序和使用的数据，其成本高，容量小，但速度快，外部存储器可用于长期保存大量程序和数据，其成本低，容量大，但速度较慢。		*输入设备和输出设备统称为外部设备，简称外设或I / O设备，用户实现人机交互和机间通信。微型机中常用的输入设备有键盘，鼠标等，输出设备有显示器，打印机等。


* C：什么是软件？件分类及举例	*计算机软件（计算机软件）是使用计算机过程中必不可少的东西，计算机软件可以使计算机按照事先预定好的顺序完成特定的功能	*计算机软件按照其功能划分为系统软件与应用软件		*系统软件：DOS（磁盘操作系统），Windows，Linux，Unix，Mac，Android，iOS 		*应用软件：Office QQ聊天空当接龙计算器英雄联盟等




### 2了解计算机基础知识之软件开发和计算机语言概述*
A:什么是软件
	* 按照特定顺序组织的计算机数据和指令的集合
* B:什么是开发
	* 软件的制作过程
* C:什么是软件开发
	* 借助开发工具与计算机语言制作软件 
* D:什么是计算机语言
	* 人与计算机之间进行信息交流沟通的一种特殊语言
* E:计算机语言的分类
	* 机器语言：
		* 机器语言是直接用二进制代码指令表达的计算机语言，指令是用0和1组成的一串代码，它们有一定的位数，并分成若干段，各段的编码表示不同的含义。
	* 汇编语言：
		* 汇编语言是使用一些特殊的符号来代替机器语言的二进制码，计算机不能直接识别，需要用一种软件将汇编语言翻译成机器语言。
	* 高级语言：  
		* 使用普通英语进行编写源代码，通过编译器将源代码翻译成计算机直接识别的机器语言，之后再由计算机执行。
		* 高级语言包括C,C++,C#,JAVA
###3了解计算机基础知识之人机交互
* A:人机交互的两种方式
	* a：命令行方式		*需要有一个控制台，输入特定的指令，让计算机完成一些操作。较为麻烦，需要记录住一些命令。	* b：图形化界面方式		*这种方式简单直观，使用者易于接受，容易上手操作。



	
### 4：掌握计算机基础知识之键盘功能键和快捷键* A：键盘功能键	* a：Tab 	* b：Shift 	* c：Ctrl 	* d：Alt 	* e：空格	 	* f： Enter 	* g：Window 	* h：上下左右键	* i：PrtSc（PrintScreen）屏幕截图* B：键盘快捷键	* a：Ctrl + A全选	* b：Ctrl + C复制	* c：Ctrl + V粘贴	* d ：Ctrl + X剪切	* e：Ctrl + Z撤销
















	* f:Ctrl+S	保存

###5掌握计算机基础知识之如何打开DOS控制台
* A:xp下如何打开DOS控制台？
	* a:开始--程序--附件--命令提示符
	* b:开始--运行--cmd--回车
	* c:win+r--cmd--回车
* B:win7下如何打开DOS控制台？
	* a:开始--所有程序--附件--命令提示符
	* b:开始--搜索程序和文件--cmd--回车
	* c:win+r--cmd--回车
* C:win8下如何打开DOS控制台
	* a:鼠标左击开始--下箭头--命令提示符
	* b:鼠标右击开始--搜索--cmd--回车
	* c:鼠标右击开始--运行--cmd--回车
	* d:win+r--cmd--回车

###6计算机基础知识之常见的DOS命令讲解
* A:d: 回车	盘符切换
* B:dir(directory):列出当前目录下的文件以及文件夹
* C:cd (change directory)改变指定目录(进入指定目录)
* D:cd.. : 退回到上一级目录
* E:cd\: 退回到根目录
* F:cls : (clear screen)清屏
* G:exit : 退出dos命令行(分割线上的需要掌握,下的了解)
* /=========================================================
* md (make directory) : 创建目录
* rd (remove directory): 删除目录
* del (delete): 删除文件,删除一堆后缀名一样的文件*.txt
* notepad 创建文件
* 删除带内容的文件夹
	* rd + /s	文件夹名称(询问是否删除)
	* rd + /q + /s 文件夹名称(直接删除)
	
###7了解Java语言基础之Java语言概述
* A:Java语言发展史
	* 詹姆斯·高斯林（James Gosling）1977年获得了加拿大卡尔加里大学计算机科学学士学位，1983年获得了美国卡内基梅隆大学计算机科学博士学位，毕业后到IBM工作，设计IBM第一代工作站NeWS系统，但不受重视。后来转至Sun公司，1990年，与Patrick，Naughton和Mike Sheridan等人合作“绿色计划”，后来发展一套语言叫做“Oak”，后改名为Java。
	* SUN(Stanford University Network，斯坦福大学网络公司) 
* B:Java语言版本
	* JDK 1.1.4		Sparkler	宝石				1997-09-12
	* JDK 1.1.5		Pumpkin		南瓜				1997-12-13
	* JDK 1.1.6		Abigail		阿比盖尔--女子名		1998-04-24
	* JDK 1.1.7		Brutus		布鲁图--古罗马政治家和将军	1998-09-28
	* JDK 1.1.8		Chelsea		切尔西--城市名			1999-04-08
	* J2SE 1.2		Playground	运动场				1998-12-04
	* J2SE 1.2.1		none		无				1999-03-30
	* J2SE 1.2.2		Cricket		蟋蟀				1999-07-08
	* J2SE 1.3		Kestrel		美洲红隼(sǔn)			2000-05-08
	* J2SE 1.3.1		Ladybird	瓢虫				2001-05-17
	* J2SE 1.4.0		Merlin		灰背隼				2002-02-13
	* J2SE 1.4.1		grasshopper	蚱蜢				2002-09-16
	* J2SE 1.4.2		Mantis		螳螂				2003-06-26
	* JAVASE 5.0 (1.5.0)	Tiger		老虎	
	* JAVASE 5.1 (1.5.1)	Dragonfly	蜻蜓	
	* JAVASE 6.0 (1.6.0)	Mustang		野马
	* JAVASE 7.0 (1.7.0)	Dolphin		海豚
* C:Java语言平台
	* J2SE(Java 2 Platform Standard Edition)标准版
		* 是为开发普通桌面和商务应用程序提供的解决方案,该技术体系是其他两者的基础，可以完成一些桌面应用程序的开发
	* J2ME(Java 2 Platform Micro Edition)小型版
		* 是为开发电子消费产品和嵌入式设备提供的解决方案
	* J2EE(Java 2 Platform Enterprise Edition)企业版
		* 是为开发企业环境下的应用程序提供的一套解决方案,该技术体系中包含的技术如 Servlet、Jsp等，主要针对于Web应用程序开发 
* C:Java语言特点
	* 简单性		
	* 解释性
	* 面向对象		
	* 高性能
	* 分布式处理	
	* 多线程
	* 健壮性		
	* 动态
	* 结构中立		
	* 安全性
	* 开源
	* 跨平台
###8掌握Java语言基础之Java语言跨平台原理
* A:什么是跨平台性
* B:Java语言跨平台原理
	* 只要在需要运行java应用程序的操作系统上，先安装一个Java虚拟机(JVM Java Virtual Machine)即可。由JVM来负责Java程序在该系统中的运行。
* C:Java语言跨平台图解
	* write once ,run anywhere!(一处编译,到处运行)
###9掌握Java语言基础之JRE和JDK的概述
* A:什么是JRE
	* 包括Java虚拟机(JVM Java Virtual Machine)和Java程序所需的核心类库等，如果想要运行一个开发好的Java程序，计算机中只需要安装JRE即可。
	* JRE:JVM+类库。 
* B:什么是JDK
	* JDK是提供给Java开发人员使用的，其中包含了java的开发工具，也包括了JRE。所以安装了JDK，就不用在单独安装JRE了。
	* 其中的开发工具：编译工具(javac.exe)  打包工具(jar.exe)等
 	* JDK:JRE+JAVA的开发工具。
* C:为什么JDK中包含一个JRE
	* 为什么JDK中包含一个JRE呢？
		* 开发完的程序，需要运行一下看看效果。
* D:JDK,JRE,JVM的作用和关系
###10了解Java语言基础之JDK的下载和安装过程图解
* A:JDK的下载
	* a:官网 http://www.oracle.com
			 ![setp1](http://img.blog.csdn.net/20171226115646361?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
	* b:演示下载流程
			 ![step2](http://img.blog.csdn.net/20171226115946781?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			 ![step3](http://img.blog.csdn.net/20171226120003560?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
* B:JDK的安装
	* a:傻瓜式安装
		* 双击安装程序，然后一路next即可(但是不建议)
	* b:安装的推荐方式
		* 安装路径不要有中文或者特殊符号如空格等。
		* 所有和开发相关的软件最好安装目录统一。
			* 举例：我的JDK安装路径
				* G:\ProgramFiles\Java\jdk
		* 当提示安装JRE时，可以选择不安装。建议还是安装上。
	* c:演示安装流程
		* 可以先在d盘建立一个文件夹ProgramFiles
		*  然后截图演示安装过程
			 ![安装Step1](http://img.blog.csdn.net/20171226121541412?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			 ![安装Step2](http://img.blog.csdn.net/20171226121620336?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			![安装Step3](http://img.blog.csdn.net/20171226121716279?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			![安装Step4](http://img.blog.csdn.net/20171226121734821?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
		
* C:验证安装是否成功
	* a:通过DOS命令，切换到JDK安装的bin目录下。
		* G:\ProgramFiles\Java\jdk
	* b:避免每次都需要进入到上方目录下的麻烦，可以选择配置环境变量
			 ![配置环境变量Step1](http://img.blog.csdn.net/20171226122957035?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			 ![配置环境变量Step2](http://img.blog.csdn.net/20171226123142567?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			![配置环境变量Step3](http://img.blog.csdn.net/20171226123158073?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
			*接下来就是确定、确定、确定就ok！
	*检验环境变量是否成功在DOS命令行里输入javac或java，如果正常显示一些内容，说明安装成功并且配置环境变量成功。
		![检验是否成功](http://img.blog.csdn.net/20171226123444646?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQva2VzZTc5NTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
		
###11了解Java语言基础之JDK安装路径下的目录解释
* a:bin目录：该目录用于存放一些可执行程序。
	* 如javac.exe（java编译器）、java.exe(java运行工具)，jar.exe(打包工具)和* javadoc.exe(文档生成工具)等。
* b:db目录：db目录是一个小型的数据库。
	* 从JDK 6.0开始，Java中引用了一个新的成员JavaDB，这是一个纯Java实现、开源的数据库管理系统。这个数据库不仅轻便，而且支持JDBC 4.0所有的规范，在学习JDBC 时，不再需要额外地安装一个数据库软件，选择直接使用JavaDB即可。
* c:jre目录："jre"是 Java Runtime Environment 的缩写，意为Java程序运行时环境。此目录是Java运行时环境的根目录，它包括Java虚拟机，运行时的类包，Java应用启动器以及一个bin目录，但不包含开发环境中的开发工具。
* d:include目录：由于JDK是通过C和C++实现的，因此在启动时需要引入一些C语言的头文件，该目录就是用于存放这些头文件的。
* e:lib目录：lib是library的缩写，意为 Java 类库或库文件，是开发工具使用的归档包文件。
* f:src.zip文件：src.zip为src文件夹的压缩文件，src中放置的是JDK核心类的源代码，通过该文件可以查看Java基础类的源代码。

###12了解Java语言基础之Java开发工具介绍
* A:notepad(微软操作系统自带,也就是记事本)
* B:Editplus/Notepad++
* C:Eclipse
* D:MyEclipse
* E：STS(Spring to Suite)
	* 给大家简单的介绍一下这些工具，然后说说我们使用这些工具的顺序。
	* 初学者练基础：先notepad，然后Editplus(培养代码感)
	* 熟练之后选择：MyEclipse、Eclipse、STS都可以。

###13掌握Java语言基础之HelloWorld案例的编写和运行
* A:定义类
* B:写main方法
* C:写输出语句
* D:Java程序开发运行与工作原理
* E:编译和运行程序

		class HelloWorld {
			public static void main(String[] args) {
				System.out.println("HelloWorld");
			}
		}
	
###14掌握Java语言基础之HelloWorld案例常见问题
* A:找不到文件(都演示一下，让学生看看出现的都是什么问题)
	* a:文件扩展名隐藏导致编译失败
	* b:文件名写错了
* B:单词拼写问题(都演示一下，让学生看看出现的都是什么问题)
	* a:class写成Class
	* b:String写成string
	* c:System写成system
	* d:main写成mian
* C:括号匹配问题(都演示一下，让学生看看出现的都是什么问题)
	* a:把类体的那对大括号弄掉一个
	* b:把方法体的那对大括号弄掉一个
	* c:把输出语句的那对小括号弄掉一个
* D:中英文问题(都演示一下，让学生看看出现的都是什么问题)
	* a:提示信息：错误: 非法字符: \????的格式
	* 注意：java编程中需要的基本上都是英文字符

###15掌握Java语言基础之Java语言的书写格式(约定俗成)
* 1,大括号要对齐,并且成对写
* 2,左大括号前面有空格
* 3,遇到左大括号要缩进,Tab
* 4,方法和程序块之间加空行让程序看起来清晰
* 5,并排语句之间加空格,例如for语句
* 6,运算符两侧加空格

###16掌握Java语言基础之path环境变量的作用及配置方式1
* A:在JDK的bin目录下开发程序容易产生的问题
	* a:如果文件过多，不方便管理
	* b:删除自己写过的不需要的文件，可能不小心把JDK自带的工具给删除了
* B:如何解决问题呢
	* notepad这样的命令为什么在任何路径下都能够执行,配置path环境变量
* C:配置方式
	* a:xp系统
		* 右键点击桌面计算机→选择属性→选择高级选项卡→点击环境变量→下方系统变量中查找path→双击path→将jdk安装目录下的bin目录添加到最左边并添加分号。
	* b:win7/win8系统
		* 右键点击桌面计算机→选择属性→选择高级系统设置→选择高级选项卡→点击环境变量→下方系统变量中查找path→双击path→将jdk安装目录下的bin目录添加到最左边并添加分号。
* path配置的是可执行的文件.exe,配置后可以在不同的盘符下访问path路径下的可执行文件

###17掌握Java语言基础之Path环境变量的配置方式2
* A:先配置JAVA_HOME
* B:再修改path
* C:最后说一下path是有先后顺序关系的

###18了解Java语言基础之classpath环境变量的作用及其配置
* A:为什么要配置classpath
* B:classpath配置的原理
* C:如何配置classpath

* path和classpath的区别
	* path配置的是可执行的文件.exe,配置后可以在不同的盘符下访问path路径下的可执行文件
	* classpath配置的java的类文件,就是.class文件

###19了解Java语言基础之Editplus开发程序并编译运行
* A:配置快捷键编译运行
* B:去除备份文件

###20掌握Java语言基础之注释概述及其分类
* A:什么是注释
* B:注释的分类及讲解
	* 文档注释目前不讲，说后面讲解

* 注释的作用
	* A:解释说明程序
	* B:帮助我们调试错误
	
###21掌握Java语言基础之关键字的概述和使用
* A:什么是关键字
	* 被Java语言赋予特定含义的单词 
* B:关键字的特点
	* 组成关键字的字母全部小写 
* C:常见关键字
	* public static void class等 
* D:关键字的注意事项
	* goto和const作为保留字存在,目前并不使用,类似Editplus这样的高级记事本,针对关键字有特殊的颜色标记，非常直观 

###22掌握Java语言基础之标识符的概述和组成规则
* A:什么是标识符
	* 就是给类,接口,方法,变量等起名字时使用的字符序列 
* B:标识符的组成规则
	* 英文大小写字母
	* 数字字符
	* $和_ 
* C:标识符注意事项
	* 1,不能使用关键字
	* 2,不能数字开头 

###23了解Java语言基础之标识符中常见的命名规则
* 见名知意
* A:包
	* 最好是域名倒过来,要求所有的字母小写 
* B:类或者接口
	* 如果是一个单词首字母大写
	* 如果是多个单词每个单词首字母大写(驼峰标识) 
* C:方法或者变量
	* 如果是一个单词全部小写
	* 如果是多个单词,从第二个单词首字母大写 
* D:常量
	* 如果是一个单词,所有字母大写
	* 如果是多个单词,所有的单词大写,用下划线区分每个单词 
