* 

## 第一章 计算机基础知识

### 1.1 基础班介绍

​	Hello，各位同学大家好，从现在开始，我们会从0开始一点一点的打开Java编程世界的大门。

#### Java基础班分类：

* 计算机基础知识
* Java基础语法
* 编程思维的建立



### 1.2 计算机简介

​	计算机俗称电脑，是第二次世界战争时，美国国防部利用它来进行弹道计算。第一台通用计算机叫做：ENIAC。当时计算机是一个庞然大物，用了18000个电子管，占地170平方米，重达30吨，耗电功率约150千瓦，每秒钟可进行5000次运算。

![ ENIAC](img\ENIAC.png)

​	随着时间和科技的不断进步，直到发展到了我们今天使用到的笔记本电脑。但需要知道的是，不管计算机发展到什么程度，本质都是进行数据计算和处理。

![计算机发展](img\计算机发展.png)

### 1.3 计算机硬件和软件

#### 1.3.1 计算机硬件

​	冯·诺依曼提出了计算机硬件分类：

* 运算器
* 控制器
* 存储器
* 输入设备
* 输出设备

##### 运算器和控制器

​	运算器和控制器合在一起就是现在的CPU。CPU就是计算机的大脑。

##### 输入设备

​	目前的输入设备有鼠标和键盘。把自己的一些数据交给计算机就是通过这些输入设备进行操作的。

##### 存储器

​	存储器就是硬盘和内存。

​	硬盘：永久存储。

​	内存：临时存储。

##### 输出设备

​	目前最为常见的输出设备就是显示器，计算机把最终的结果展现出来给我们看到。除此之外，输出设备还有打印机。

#### 1.3.2 计算机软件

* 系统软件
* 应用软件

##### 系统软件

​	简单理解就是操作系统。平时所说的安装系统，其实就是安装系统软件而已。常见的系统软件有平时用的最多的windows，还有苹果电脑MacOS，还有就业班会学习到的Linux。下面从左到右分别为windos操作系统图标，MacOS操作系统图标，Linux操作系统图标。

   ![计算机发展](img\windows.png)                                      ![计算机发展](img\macos.png)

​                     

![计算机发展](img\linux.png)



##### 应用软件

​	应用软件就非常的熟悉了。我们平时使用的基本都是应用软件，比如QQ，微信，Stream平台。在今后我们开发的大多数也是应用软件。

​               ![计算机发展](img\qq.jpg)      ![计算机发展](img\微信.png)       ![计算机发展](img\stream.jpg)

##### 应用软件架构分类

* C/S: Client/Server 客户端/服务器端：

  在用户本地有一个客户端程序，在远程有一个服务器端程序 。

  比如：QQ，微信，Stream。

* B/S: Browser/Server浏览器/服务器端：

  只需要一个浏览器，用户通过不同的网址，客户访问不同的服务器端程序。

  比如：京东，淘宝。

### 1.4 计算机语言

​	 人与计算机沟通交流的表达方式。

#### 计算机语言的发展

* 机器语言

  机器语言就是 0/1 代码。计算机只能识别 0 和 1。在计算机内部，无论是一部电影还是一首歌曲或是一张图片，最终保存的都是 0/1 代码。

* 汇编语言

  汇编语言就是将一串很枯燥无味的机器语言转化成英文单词。 

  比如：add 1, 2。其实就是让1和2进行相加。

  计算机在执行的时候，会先把这串英文转成0101010101的形式，再交由计算机执行。但是汇编语言比较麻烦，比如我用汇编语言给你打个招呼。代码量会非常的大。所以我们也不会学习他。

  ![计算机发展](img\汇编.png)

* 高级语言

  ​	使用普通英语进行编写源代码，通过编译器将源代码翻译成计算机直接识别的机器语言，之后再由计算机执行。这样的代码就比较符合正常人的思维逻辑。

  ​	比如，下面的这段代码。判断年龄age是否大于等于18，如果是的，就可以浏览学习网站。这样就非常符合正常人的思维逻辑，下面的这些代码，在后面的课程中都会学习。

  ```java
  int age = 18;
  if (age >= 18) {
      System.out.println("可以浏览学习网站");
  } else {     
      System.out.println("民主、文明、和谐、自由、平等、公正、法治、爱国、敬业、诚信、友善");
  }
  ```

  ​	上面的这段代码在执行的时候，会先对代码进行编译，再交由计算机执行。

  ![计算机发展](img\编译.png)

### 1.5 人机交互

#### 图形化界面

​	我们平时使用计算机都是使用图形化界面操作方法，需要打开文件，直接用鼠标双击打开即可，需要删除一个文件，直接右键点击文件选择删除即可。

#### 命令行

​	计算机刚开始出现的时候，是没有图形化界面的，都是命令行的方式操作计算的。

现在给大家介绍的是DOS命令提示符。

##### 命令行打开方式：

* 按下 win + R

![计算机发展](img\win.png)

* 在弹出的运行窗口中输入cmd + 回车

![计算机发展](img\运行.png)

* 在出现的黑屏窗口中就可以输入dos命令来操作计算机了。

  比如：shutdown -s -t 300 就可以在300秒后关机

  比如：shutdown -a 就可以取消刚刚的关机计划

![计算机发展](img\关机.png)

##### 常见的DOS命令

| 操作              | 说明                              |
| ----------------- | --------------------------------- |
| 盘符名称:         | 盘符切换。E:回车，表示切换到E盘。 |
| dir               | 查看当前路径下的内容。            |
| cd 目录           | 进入单级目录。cd itheima          |
| cd 目录1\目录2... | 进入多级目录。cd itheima\JavaSE   |
| cd ..             | 回退到上一级目录。                |
| cd \              | 回退到盘符目录。                  |
| cls               | 清屏。                            |
| exit              | 退出命令提示符窗口。              |

##### 思考：打开QQ

​	如何使用DOS窗口去打开QQ呢？

* 在图形化界面中直接找到qq的安装路径，双击QQ.exe就可以了
* 在图形化界面中，可以先切换到QQ安装的盘符，然后利用cd命令进入到qq安装目录的bin目录下。再输入qq即可。


## 第二章 Java程序初体验

### 2.1 Java背景介绍

####  2.1.1 Java名称的由来

​	在最初，Java语言是叫做oak（橡树）。是因为刚开始公司门口有一颗橡树。所以就叫做橡树。然后发现oak已经被美国橡树公司注册了，就不能再继续使用了。所以需要改名。而程序员最爱喝的是咖啡，盛产咖啡的岛叫做爪哇岛，由此语言就叫做Java了。

#### 2.2.2 Java语言的发展

​	Java语言是美国Sun公司（Stanford University Network），在1995年推出的高级的编程语言。所谓编程语言，是计算机的语言，人们可以使用编程语言对计算机下达命令，让计算机完成人们需要的功能。2009年，Sun公司被甲骨文公司收购，所以我们现在访问oracle官网即可：https://www.oracle.com

Java语言共同创始人之一：詹姆斯·高斯林 （James Gosling），被称为“Java之父”

![计算机发展](img\James.png)

#### 2.2.3 Java的三大平台

* JavaSE

  ​	Java 语言的（标准版），用于桌面应用的开发，是其他两个版本的基础。

* JavaME

  ​	Java 语言的（小型版），用于嵌入式消费类电子设备。

* JavaEE

  ​	Java 语言的（企业版），用于 Web 方向的网站开发。

##### JavaSE：

​	Java 语言的（标准版），用于桌面应用的开发，是其他两个版本的基础。

学习 Java SE 的目的 : 为今后要从事的 Java EE 开发，打基础。 

桌面应用 ：

​	用户只要打开程序，程序的界面会让用户在最短的时间内找到他们需要的功能，同时主动带领用户完成他们的工作并得到最好的体验。

​	比如：操作系统里面的计算器。

​	比如：坦克大战小游戏。

​          ![计算机发展](img\计算机.png)       ![计算机发展](img\坦克大战.png)

##### JavaME：

​	Java ME : Java 语言的（小型版），用于嵌入式消费类电子设备。

比如：以前诺基亚的塞班系统，里面的一些应用程序就是用JavaME开发的。

但是随着塞班系统渐渐的没落，JavaME也退出了历史舞台。

![计算机发展](img\诺基亚.png)

##### JavaEE：

​	Java 语言的（企业版），用于 Web 方向的网站开发。

网站：通过跟后台服务器的交互，将查询到的真实数据再通过网页展示出来。

简单理解：网站 = 网页浏览器数据展示 + 后台服务器

比如：

![计算机发展](img\京东.jpg)

![计算机发展](img\天猫.jpg)

![计算机发展](img\网银.jpg)

### 2.2 Java跨平台工作原理

#### 2.2.1 平台

​	平台：指的是操作系统。 

* Windows
* MacOS
* Linux

#### 2.2.2 跨平台

​	Java 程序不需要进行任何修改，就可以在任意操作系统上运行。 

注意：不是所有的语言都具备这样的特征。比如：C#只能在windows上运行。

#### 2.2.3 Java实现跨平台的原理

​	编写的Java代码并不是直接运行在操作系统当中的。而是运行在安装的JVM虚拟机中的。每一个操作系统都会对应各自版本的虚拟机。

​	![计算机发展](img\跨平台原理.png)

思考：JVM 本身是否可以跨平台

JVM 虚拟机本身不允许跨平台，每一个操作系统都有对应版本的虚拟机。允许跨平台的是 Java 程序

### 2.3 JRE和JDK介绍

- **JRE ** (Java Runtime Environment) ：是Java程序的运行时环境，包含`JVM` 和运行时所需要的`核心类库` 。
- **JDK**  (Java Development Kit)：是Java程序开发工具包，包含`JRE` 和开发人员使用的工具。

我们想要运行一个已有的Java程序，那么只需安装`JRE` 即可。

我们想要开发一个全新的Java程序，那么必须安装`JDK` 。

> 小贴士：
>
> 三者关系： JDK > JRE > JVM

![计算机发展](img\JDKJREJVM.jpg)

### 2.4 JDK的下载和安装

#### 2.4.1 Java的发展历史

- 1995年Sun公司推出Java语言
- 1996年发布Java 1.0版本
- 1997年发布Java 1.1版本
- 1998年发布Java 1.2版本
- 2000年发布Java 1.3版本
- 2002年发布Java 1.4版本
- 2004年发布Java 5.0版本
- 2006年发布Java 6.0版本
- 2009年Oracle甲骨文公司收购Sun公司
- 2011年发布Java 7.0版本
- 2014年发布Java 8.0版本
- 2017年9月发布Java 9.0版本
- 2018年3月发布Java 10.0版本
- 2018年9月发布Java 11.0版本
- 2019年3月发布Java 12.0版本
- 2019年9月发布Java 13.0版本
- 2020年3月发布Java 14.0版本

>小贴士：
>
>Java5.0：里程碑性质的版本，也是第一个大版本号更新。
>
>Java8.0：企业中用的最多的版本。
>
>Java14.0：目前最新的，也是课程中学习的版本。

#### 2.4.2 下载

* 通过官方网站获取JDK

		网址：http://www.oracle.com

![计算机发展](img\oracle.png)

* 拖动到页面的最下方，点击"JAVA SE14 download"

![计算机发展](img\下载1.png)

* 点击下载

![计算机发展](img\下载2.png)

* 针对不同的操作系统，需要下载对应版本的JDK。

如果是windows64位的操作系统，可以点击下方红框的连接进行下载

![计算机发展](img\下载3.png)

#### 2.4.3 安装

* 在day01的资料文件夹中，已经下载好了，双击打开安装包

![计算机发展](img\安装0.png)

* 双击打开之后，直接点击下一步

![计算机发展](img\安装1.png)

* 选择安装路径，再点击下一步

![计算机发展](img\安装2.png)

* 等待进度条完成

![计算机发展](img\安装3.png)

* 点击关闭，安装成功。

![计算机发展](img\安装4.png)

>小贴士：
>安装路径不要有中文，不要有空格
>找一个固定的文件夹专门安装所有跟开发相关的软件，方便管理。

#### 2.4.4 JDK的安装目录介绍

| 目录名称 | 说明                                                         |
| -------- | ------------------------------------------------------------ |
| bin      | 该路径下存放了JDK的各种工具命令。javac和java就放在这个目录。 |
| conf     | 该路径下存放了 JDK 的相关配置文件                            |
| include  | 该路径下存放了一些平台特定的头文件                           |
| jmods    | 该路径下存放了 JDK 的各种模块                                |
| legal    | 该路径下存放了 JDK 各模块的授权文档                          |
| lib      | 该路径下存放了 JDK 工具的一些补充 JAR 包                     |

### 2.5 HelloWorld

#### 2.5.1 HelloWorld的仪式感

​	HelloWorld中文意思是『你好世界』。该程序的效果就是在让程序帮我们展示一段文字，内容为 HelloWorld。

​	程序员在学习任何一门编程语言，第一个入门案例，都是 HelloWorld。

#### 2.5.2 书写步骤

* 新建一个Java文件，修改名称为HelloWorld.java 
* 用记事本打开HelloWorld.java文件，输写程序内容 

![计算机发展](img\helloworld.png)

* 保存（快捷键**Ctrl+s**）

* 编译文件

  ​	javac HelloWorld.java 

* 运行文件

  ​	java HelloWorld 

>小贴士：
>
>新建的HelloWorld.java文件一定要放在JDK安装目录的bin目录下面。

#### 2.5.3 HelloWorld代码详解

```java
public class HelloWorld {
	public static void main(String[] args) {
		System.out.println("HelloWorld");
	}
}
```

class : 定义一个类，后面跟上的是类名名称。类是Java中最基本的组成单元。

第二行代码：程序执行时的入口点，main方法称之为主方法。

第三行代码：使程序能够输出打印双引号中包裹的内容。

### 2.6 Path环境变量的配置

#### 2.6.1配置环境变量的目的

​	在刚刚写的代码中，只能存放在bin目录下，才能使用 javac 和 java 工具。如果我想把代码存放在任意的目录下，在任意的目录下都可以使用javac 和 java 工具该怎么办呢？
就可以把 javac 和 java配置到环境变量当中。

#### 2.6.2 配置步骤

* 按下 Win键 + E ，找到计算机 

![计算机发展](img\环境变量1.png)

* 右键点击计算机，选择属性

![计算机发展](img\环境变量2.png)

* 点击高级系统设置

![计算机发展](img\环境变量3.png)

* 选择高级，再点击下面的环境变量

![计算机发展](img\环境变量4.png)

* 点击系统变量下面的新建

![计算机发展](img\环境变量5.png)

* 会弹出这样的界面

![计算机发展](img\环境变量6.png)

* 变量名后面输入：JAVA_HOME 

  变量值后面：将JDK的安装路径复制过来，

  注意：不带bin目录

  操作完毕点击确定

![计算机发展](img\环境变量7.png)

* 选择Path。

  此处还是要选择下方系统变量中的Path。

  点击编辑

![计算机发展](img\环境变量8.png)

* 在弹出的页面中点击编辑文本

![计算机发展](img\环境变量9.png)

* 点击完毕之后会弹出这样的界面。

  注意：里面的内容不能删除。

![计算机发展](img\环境变量10.png)

* 在变量值的最前面输入：

  %JAVA_HOME%\bin; 输入完毕确定。

  其中使用两个百分号包住JAVA_HOME，表示引用了JAVA_HOME里面的值。

  分号，表示多个环境变量之间的间隔。

  注意：所有符号一定要是英文状态下的。

![计算机发展](img\环境变量11.png)

* 打开CMD，输入java回车。

  如果出现一长串很多的白色文字，表示配置成功。

![计算机发展](img\环境变量13.png)

### 2.7 注释

#### 2.7.1 什么是注释

​	**注释**：就是对代码的解释和说明。其目的是让人们能够更加轻松地了解代码。为代码添加注释，是十分必须要的，它不影响程序的编译和运行。

#### 2.7.2 注释的分类

- 单行注释

  ​	格式：`// 注释信息`

- 多行注释

  ​	格式： `/* 注释信息 */`

- 文档注释

  ​	格式：`格式：/** 注释信息 */`

  ​	文档注释目前用不上，了解即可。

#### 2.7.3 注释的使用

```java
//这是通过class创建了一个类，类名叫做HelloWorld
public class HelloWorld {
    /*
    	这是程序的入口点，main方法也称之为主方法。
    	如果代码中没有编写主方法，将无法运行
    */
	public static void main(String[] args) {
        //这是一条打印语句，可以将双引号中所包裹的内容打印在控制台。
		System.out.println("HelloWorld");
	}
}
```

#### 2.7.4 注释的注意点

​	注释内容不会参与编译和运行。

举例：哪怕注释写成下面这个样子，在运行的时候也不会有问题。

​	  因为注释的内容是不会参与编译和运行的。

![计算机发展](img\注释.png)



## 第三章 IDEA

### 3.1 IDEA概述

​	IDEA全称IntelliJ IDEA，是用于Java语言开发的集成环境，它是业界公认的目前用于Java程序开发最好的工具。

**集成环境：**

​	把代码编写，编译，执行，调试等多种功能综合到一起的开发工具。

### 3.2 IDEA的下载和安装

#### 3.2.1 下载

​	可以到官方网站自行下载，网址为：https://www.jetbrains.com/idea

​	今天的资料中，对应的安装包也提高给大家了。

#### 3.2.2 安装

* 到资料文件夹中，双击安装包。
* 点击next，准备安装

![计算机发展](img\idea安装1.png)

* 点击Browse修改安装路径。

  修改完毕点击next

![计算机发展](img\idea安装2.png)

* 勾选64-bit launcher。表示在桌面新建一个64位的快捷方式。

  其他的不要勾选。

  点击next。

![计算机发展](img\idea安装4.png)

* 点击Install，准备安装。

![计算机发展](img\idea安装5.png)

* 等进度条读取完毕之后，会有最终界面提示。

  点击finish即可。

![计算机发展](img\idea安装6.png)

* 第一次启动会询问，是否导入一些设置。

  选择第二个不导入，保持默认设置，再点击OK。

![计算机发展](img\idea安装7.png)

* 选择背景主题

  左边是黑色背景。右边是白色背景。

  这个可以根据自己的喜好来选择。

  选择完毕点击右下角的next

![计算机发展](img\idea安装8.png)

* 在本界面让我们购买idea。

  因为我们是学习阶段，所以可以使用免费使用30天。

  点击第一排第二个。Evaluate for free

![计算机发展](img\idea安装9.png)

* 点击蓝色的Evaluate，就可以开始免费试用30天了。

![计算机发展](img\idea安装10.png)

* 当看到这个界面，就表示idea已经成功安装完毕

  可以点击右上角关闭。

![计算机发展](img\idea安装11.png)

### 3.3 IDEA中层级结构介绍

#### 3.3.1 结构分类

* project（项目、工程）
* module（模块）
* package（包）
* class（类）

#### 3.3.2 结构介绍

​	为了让大家更好的吸收，package这一层级，我们后面再学习，先学习最基础的project、module、class。

##### project（项目、工程）

​	淘宝、京东、黑马程序员网站都属于一个个项目，IDEA中就是一个个的Project。

##### module（模块）

​	在一个项目中，可以存放多个模块，不同的模块可以存放项目中不同的业务功能代码。在黑马程序员的官方网站中，至少包含了以下模块：

* 论坛模块
* 报名、咨询模块

为了更好的管理代码，我们会把代码分别放在两个模块中存放。

##### package（包）

​	一个模块中又有很多的业务，以黑马程序员官方网站的论坛模块为例，至少包含了以下不同的业务。

* 发帖
* 评论

为了把这些业务区分的更加清楚，就会用包来管理这些不同的业务。

##### class（类）

​	就是真正写代码的地方。

#### 3.3.3 小结

* 层级关系

  ​	project - module - package - class

* 包含数量

  ​	project中可以创建多个module
  ​	module中可以创建多个package
  ​	package中可以创建多个class

  ​	这些结构的划分，是为了方便管理类文件的。

### 3.4 IDEA中的第一个代码

##### 3.4.1 操作步骤

* 创建Project 项目
* 创建Module 模块
* 创建class  类
* 在类中编写代码
* 完成编译运行

##### 3.4.2 分步图解

* 双击启动图标

   ![计算机发展](img\idea使用1.png)

* 首先要新建一个项目

  点击creat new project

  ![计算机发展](img\idea1.png)

* 我们要从0开始写代码，所以新建一个空的什么都没有的项目。

  点击左下方的Empty Project

  再点击右下角的next

![计算机发展](img\idea2.png)

* 输入项目的名称

  输入项目的存放路径

![计算机发展](img\idea3.png)

* 点击ok。idea会帮助我们在本地创建一个项目文件夹

![计算机发展](img\idea4.png)

* 点击Module，准备新建一个模块

![计算机发展](img\idea5.png)

* 点击+

  再点击New Module

![计算机发展](img\idea6.png)

* 我们要编写Java代码，所以要新建一个Java模块。

  点击Java

  再点击右下角的next

![计算机发展](img\idea7.png)

* 输入模块的名称

  再点击右下角的Next

![计算机发展](img\idea8.png)

* 成功新建一个模块之后，中间就会出现刚刚新建的模块

  点击右下角的OK

![计算机发展](img\idea9.png)

* 回到主界面

  展开刚刚新建的模块

  右键点击src，选择New，选择Java Class

![计算机发展](img\idea10.png)

* 输入类名

  再按回车

![计算机发展](img\idea11.png)

* 由于字体比较小

  所以，我们要设置一下字体。

  点击File，选择Setting。

![计算机发展](img\idea12.png)

* 搜索一下font

  在右边可以输入Size的数值来调节代码字体的大小。

  设置完毕后点击右下角的OK

![计算机发展](img\idea13.png)

* 编写代码

![计算机发展](img\idea14.png)

* 运行代码

  右键空白处，点击Run

![计算机发展](img\idea15.png)



* 最下面会弹出控制台。

  所有输出语句中的内容，都会在控制台上展示。

![计算机发展](img\idea16.png)

### 3.5 IDEA中类的相关操作

#### 3.5.1 类的相关操作

* 新建类文件
* 删除类文件
* 修改类文件

#### 3.5.2 新建类文件

* 所有的Java代码都会写在src文件夹当中。

  所以，右键点击src，选择new，点击Java Class

  ![计算机发展](img\新建类1.png)

* 输入类名，再按回车

		![计算机发展](img\新建类2.png)

* 新建完毕

![计算机发展](img\新建类3.png)

#### 3.5.3 修改类名

* 右键点击想要修改的文件

  点击Refactor

  再点击Rename

![计算机发展](img\修改类名1.png)

* 输入想要修改的名字

  输入完毕点击下面的Refactor

![计算机发展](img\修改类名2.png)

* 文件名和类名均已修改成功

  ![计算机发展](img\修改类名3.png)

#### 3.5.4 删除类文件

* 想要删除哪个文件，就右键点击该文件

  选择Delete即可

![计算机发展](img\删除类文件1.png)

* 在弹出的界面中点击OK，确定删除

![计算机发展](img\删除类文件2.png)

>小贴士：
>
>此时删除是不走回收站的，直接从硬盘中删掉了。

### 3.6 IDEA中模块的相关操作

#### 3.6.1 模块的相关操作

* 新建模块
* 删除模块
* 修改模块
* 导入模块

#### 3.6.2 新建模块

* 点击File，选择Project Structure

![计算机发展](img\新建模块1.png)

* 选择Module

![计算机发展](img\新建模块2.png)

* 点击+

  选择New Module

![计算机发展](img\新建模块3.png)

* 要创建一个Java模块，所以选择第一个Java

  点击右下角的Next

![计算机发展](img\新建模块4.png)

* 输入模块的名称

  点击右下角的Finish

![计算机发展](img\新建模块5.png)

* 成功新建完毕之后，在中间空白区域就出现了刚刚新建的模块

  点击右下角的OK

![计算机发展](img\新建模块6.png)

* 在主界面中，也会出现刚刚新建的模块

![计算机发展](img\新建模块7.png)

#### 3.6.3 删除模块

* 右键点击模块

  选择Remove Module

![计算机发展](img\删除模块1.png)

* 选择Remove，表示确定删除

![计算机发展](img\删除模块2.png)

* 此时发现，在IDEA列表页面，删除的模块已经不在了。

![计算机发展](img\删除模块3.png)

>小贴士：
>
>此时删除仅仅是从IDEA列表中的删除，在本地硬盘中还是存在的。

#### 3.6.4 修改模块

* 右键点击模块名

  选择Refactor

  再选择Rename

![计算机发展](img\修改模块名1.png)

* 选择第三个修改模块名和本地文件夹名

  点击OK

![计算机发展](img\修改模块名3.png)

* 输入要修改的新的模块名

  输入完毕点击Refactor

![计算机发展](img\修改模块名4.png)

* 回到主界面，就发现模块名和文件夹名都已经修改完毕

![计算机发展](img\修改模块名5.png)



#### 3.6.5 导入模块

* 点击File，选择Project Structure

![计算机发展](img\导入模块1.png)

* 选择Module

  点击+

  选择Import Module

![计算机发展](img\导入模块2.png)

* 从本地硬盘中选择要导入的模块

  再点击OK

![计算机发展](img\导入模块3.png)

* 不断点击Next

![计算机发展](img\导入模块4.png)

* 如果中间出现提示框，则点击Overwrite

  然后继续点击右下角的Next

![计算机发展](img\导入模块5.png)

* 一直点到finish为止

![计算机发展](img\导入模块6.png)

* 成功导入后，在中间位置就会出现导入的模块信息

![计算机发展](img\导入模块7.png)

* 在主界面中也会出现导入的模块信息

![计算机发展](img\导入模块8.png)



* 展开模块点击模块中的Java文件，会发现代码报错。

  是因为导入模块跟JDK没有关联导致。

![计算机发展](img\导入模块9.png)



* 可以点击右上角的Setup SDK

  再选择已经安装的JDK版本即可

![计算机发展](img\导入模块10.png)

* 导入完毕之后，代码就恢复正常不会报错了

![计算机发展](img\导入模块11.png)

### 3.7 IDEA中项目的相关操作

#### 3.7.1 项目的相关操作

* 关闭项目
* 打开项目
* 修改项目
* 新建项目

#### 3.7.2 关闭项目

* 点击File，选择Close Project即可

![计算机发展](img\关闭项目1.png)

* 刚刚操作的项目就已经关闭了

  左侧是项目列表，如果要再次打开该项目，直接点击即可。

  右侧有create new project，可以再建一个新的项目

![计算机发展](img\关闭项目2.png)

* 鼠标放在项目上，后面会出现一个叉。

  如果点击了这里的叉，会在IDEA的列表中删除。不会删除本地硬盘上的项目。

![计算机发展](img\关闭项目3.png)

#### 3.7.3 打开项目

* 在本界面还可以打开本地已经存在的项目

  点击Open or Import

![计算机发展](img\打开项目1.png)

* 选择要打开的项目

  点击OK

![计算机发展](img\打开项目2.png)

* 项目就被打开了。

![计算机发展](img\打开项目3.png)

#### 3.7.4 修改项目

* 点击File，选择Project Structure

![计算机发展](img\修改项目1.png)

* 在这个界面，默认是Module

  所以，要先点击Project

  在右侧页面中，输入新的项目名称

  修改JDK版本和编译版本都变成JDK14

  再点击OK

![计算机发展](img\修改项目2.png)

* 此时发现，项目名称已经修改完毕

![计算机发展](img\修改项目3.png)

* 但是本地文件夹的名字还没有修改

![计算机发展](img\修改项目4.png)

* 需要先关闭当前项目

![计算机发展](img\关闭项目1.png)

* 点击项目后面的叉，从列表中移除项目

![计算机发展](img\关闭项目3.png)

* 到本地硬盘中手动修改文件夹的名称

 ![计算机发展](img\修改项目5.png)

* 点击Open or Import重新打开项目

![计算机发展](img\打开项目1.png)

* 选择修改之后的项目

  点击OK

![计算机发展](img\修改项目6.png)

* 此时会发现，项目名称和本地硬盘文件夹的名称都已经修改完毕了

![计算机发展](img\修改项目7.png)

#### 3.7.5 新建项目

* 点击File

  选择New

  点击Project

![计算机发展](img\新建项目1.png)

* 同样还是创建一个什么都没有的空项目

![计算机发展](img\新建项目2.png)

* 输入项目的名称

  点击右下角的finish

![计算机发展](img\新建项目3.png)

* IDEA循环是否需要帮我们在本地创建一个新的文件夹

  点击OK

![计算机发展](img\新建项目4.png)

* 询问是在本窗口打开还是在一个新的窗口打开。

  可以点击New Window，在一个新的窗口打开。

![计算机发展](img\新建项目5.png)

* 此时就出现了两个窗口，在一个新的窗口打开了新的项目

![计算机发展](img\新建项目6.png)

### 3.8 TODO

##### 格式：

​	//TODO：内容

##### 作用：

​	标记我们的代码，一般是用来表示待完成，或者待解决的部分。

##### 举例1：

```java
public class A {
    //TODO: 缺少一个主方法需要补齐
}
```

##### 举例2：

```java
public class B {
    public static void main(String[] args) {
        //TODO:缺少一个打印语句需要补齐
    }
}
```

##### 举例3：

```java
public class C {
    // TODO:缺少一个主方法需要补齐
    // TODO:缺少一个打印语句需要补齐
}
```

##### 使用：

​	在idea主界面的左下角，会有一个TODO按钮。

​	点击一下TODO按钮之后，会把项目中所有标记了TODO的都展示出来。

​	当我们点击其中一个时，代码区域就会自动跳转。

![计算机发展](img\todo.png)





