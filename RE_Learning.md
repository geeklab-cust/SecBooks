## 二进制安全学习内容，仅供参考
Windows安全，Linux安全，Android安全，WEB安全与渗透测试，漏洞分析与挖掘，逆向工程，VT与X64


#### A，入门篇

0． C语言精华复习与归纳、数据结构与算法、保护模式

1． 内核hello world编写、编译、和测试

2． 内核框架理解

3． 内核调试（Windbg使用技巧，反调试，反反调试，花指令，蓝屏分析等）



#### B，基础篇

4． 内核级文件与注册表操作

5． 中断请求级别（IRQL）

6． 同步与多线程

7． 内核数据结构

8． 应用程序与内核通信与弹窗



#### C，中级篇

9． HOOK(SSDT,SHADOWSSDT,INLINE, DLL注入与R3HOOK等)

10． 文件过滤驱动（sfilter/minifilter）

11． 网络过滤驱动(tdi/ndis/wfp、netfilter)

12． 软件调试(windbg/ida/ollydbg)

13． 逆向工程（X86汇编，IDA，PC端、移动端逆向工程）

14． Linux内核安全开发起步

15． Android移动安全

（NDK底层开发，Android内核编译与裁剪，SMALI汇编，ARM汇编，HOOK，ROOT，动态调试，逆向，加、脱壳，病毒分析）
16． 漏洞分析、挖掘与安全编程
（如缓冲溢出，任意地址写任意数据，ROP,TOCTTOU,Double-fetch,OOB,UAF）
17． Web安全与渗透测试
（SQL注入，XSS，CSRF，命令执行，代码执行，反序列化等各种Web漏洞分析与预防， metasploit渗透测试，社会工程学，APT攻击等）



#### D，高级篇

18. 企业实用安全技术详解(new)

19．主防（HIPS）

20．沙盘（SANDBOX）

21．防火墙（TDI/NDIS/WFP）

22．ARK ANTI-ROOTKIT/基于MBR、UEFI和BIOS的BOOTKIT技术分析与查杀

23．VT技术与X64 HOOK，调试器

24．程序逆向，病毒分析

25．Android手机安全

26．毕业设计



#### 1，C语言&数据结构

Hello world

数据类型与变量

数的表示与存储

运算符与表达式

语句（循环，条件，顺序）

数组

字符串

函数，调用约定

头文件，源文件，编码风格

指针

结构体、联合体、枚举类型

文件操作

宏定义

预编译处理

位运算

链表

队列

栈

树

HASH表

排序

查找

计算机体系结构的理解

操作系统的理解

CPU，内存，寄存器，位数，进程，线程，调度等理解

文件系统

TCP/IP网络协议,HTTP协议

内存寻址

编译原理的理解




#### 2，C++面向对象思想

封装

继承

多态

stl模板库（SET，LIST,MAP等）



#### 3，Java语言入门学习

java语法

面向对象

设计模式



#### 4，Python脚本语言学习

Python语法

Python数据结构与算法(list,tuple,dict,sort)

Python文件IO

Python网络通信

Python网络爬虫与格式化数据抽取



#### 5，汇编语言学习

汇编版hello world

CPU与寄存器

CISC VS RISC指令集

Intel汇编与AT&T汇编

内存寻址模式（实模式分段模型、保护模式扁平模型）

汇编指令学习（数据传送指令，算术指令，串操作指令，控制转移指令等)
汇编程序设计

X64汇编

C语言本质与汇编联系

（调试版/发行版汇编，调用约定，传参，循环语句，结构体、数组访问，i++/++i的汇编分析）



#### 6，加密解密理论与应用实践

对称加密、非对称加密、HASH散列，DES/3DES，AES，blowfish,twofish，RSA，MD5，SHA等



### 第二阶段：平台安全开发篇

（从应用到底层深入学习3大系统）：



#### 1，windows系统开发

mfc界面开发

多线程

DLL开发

R3 HOOK

驱动框架理解

驱动级文件与注册表操作

中断运行级别

同步与多线程

内核数据结构

应用程序与驱动通信与弹窗

HOOK

文件系统（sfilter/minifilter）

网络驱动(tdi/ndis/wfp)



#### 2，linux系统开发

Linux系统常用命令学习

vim学习

GCC,Makefile，SCONS编译

GDB调试

多线程

网络SOCKET编程

LINUX开源项目分析与应用开发

(mysql,memcached,json,curl,redis,nginx等）

内核的编译与裁剪

内核模块的开发与编译

内核内存分配

内核同步与互斥

内核中断上半部与下半部机制

内核HOOK与调试

基于linux内核的网络防火墙开发



#### 3，Android系统开发

Android界面与事件

Android四大组件（ACTIVITY,SERVICE,PROVIDER,RECEIVER)

Android网络编程

Android 底层NDK开发

Android ARM汇编，SMALI汇编

Android hook

Android root

Android 逆向与病毒分析



### 第三阶段：安全分析与逆向篇

#### 1，汇编语言（X86,arm）

#### 2，病毒分析与逆向

IDA PRO与OD使用

病毒分析与逆向

anti-rootkit分析

MBR bootkit分析

Android分析与逆向



#### 3，漏洞分析与安全编码

缓冲区溢出漏洞：栈溢出，堆溢出

非缓冲区溢出漏洞：SQL注入，XSS跨站点攻击，外部命令执行，PATH攻击

内核漏洞原理分析

拒绝服务

缓冲区溢出

内存篡改（任意地址写任意数据，任意地址写固定数据）

漏洞经典案例分析（冲击波，心血漏洞，web漏洞等）

系统安全机制与安全编码

漏洞挖掘(各种FUZZ工具）





#### 2，不同类型漏洞原理与实例分析

栈溢出攻击

堆溢出攻击

堆栈协同攻击heap-spray

SEH攻击

META SPLOIT快速溢出和渗透测试

ROP (Return-oriented programming)

TOCTTOU漏洞

Double-fetch漏洞

UAF（Use-After-Free）漏洞

竞争条件攻击漏洞

未初始化漏洞

OOB（out of bound）越界访问漏洞

SQL注入

XSS跨站点攻击

外部命令执行

PATH攻击



#### 3，内核漏洞原理与实例分析

拒绝服务

缓冲区溢出

内存篡改（任意地址写任意数据，任意地址写固定数据）

内核提权攻击



#### 4，漏洞经典案例分析

冲击波蠕虫攻击漏洞

心血漏洞

MS MsMpEng CVE-2017-0290微软核弹漏洞

heap spray堆栈协同攻击



#### 5，漏洞挖掘

FUZZ测试原理

FUZZ挖掘漏洞小例子

内核漏洞挖掘

IOCTL MITM FUZZ

IOCTL DRIVER FUZZ



#### 6，安全编码原则

字符串安全操作函数

输入参数严格检查

参数严进宽出原则

缓存边界与大小检查

内核安全编码七大规范

启用windows安全机制

- Security cookie

- SAFE SEH

- DEP

- ASLR

- SEHOP

- Safe Unlink

- heap cookie

SQL注入与XSS预防



#### 7，各类溢出安全问题

- 数组溢出

- 数溢出

- 栈溢出

- 指针溢出

内存泄漏预防与检测

如何避免竞争条件攻击

多线程安全编码原则

野指针安全问题





# 五，Android移动安全

1，Android应用层编程（界面，消息事件，四大组件，网络通信）

2，Android NDK底层开发

3，Android内核编译与裁剪

4，SMALI汇编

5，ARM汇编

6，HOOK与免root HOOK

7，ROOT原理，SELinux

8，无源码级动态调试

9，APK和SO逆向分析

10，APK和SO的加、脱壳

11，病毒分析



# 六，Linux内核开发

### 一，Linux系统应用编程

Linux系统常用命令学习

vim学习

GCC,Makefile，SCONS编译

GDB调试

多线程

网络SOCKET编程

LINUX开源项目分析与应用开发

(mysql,memcached,json,curl,redis,nginx等）



### 二，Linux内核开发

实模式与保护模式地址映射

内核的编译与裁剪

内核模块的开发与编译

内核内存分配

内核同步与互斥

内核中断上半部与下半部机制

内核HOOK与调试

基于linux内核的网络防火墙开发
