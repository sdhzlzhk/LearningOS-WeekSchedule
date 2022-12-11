# record
这是我关于OS秋季训练营的学习文档


## Schedule
## 2022-11-01
### 计划
   1、通过阅读 Rust 程序设计学习Rust的所有权和结构体等语法      

### 成果 
   1、明白了相对于其它有GC的语言，Rust使用所有权进行关联内存，最大限度减少堆上的重复数据，及时清理垃圾内存，感觉这个设计非常nice。        
   2、了解和学习了变量交互方式：移动、克隆 、引用、借用、slice类型等基础语法知识       
   3、了解了结构体的定义 、实例化 、方法定义等基础知识
<span id="1"></span>

## 2022-11-02
### 计划
   1、通过阅读继续学习枚举和模式匹配     
   2、学习包、crate、模块关联等知识           
   3、参加晚上线上Rustlings课程

### 成果
   1、学习了解了枚举的知识和match匹配

   2、学习了解了包、crate、模块、路径引入等知识

   3、参加了线上Rustlings课程，讲解以题为主，希望是先学习具体语法等知识。

   4、根据之前学习的内容，rustlings题目做了16道并提交  

<span id="2"></span>

## 2022-11-03

### 计划

   1、根据计划，继续学习常见集合和错误处理的章节知识    

### 成果

   1、学习并了解了vector类型、String集合、hashmap等集合类型的新增、更新、遍历、索引查找等语法

   2、学习了Rust错误处理，用panic处理不可恢复的错误；用Result处理可恢复错误，以及unwrap和expect处理，使用？运算符传播错		 误。

​    3、学习了泛型的定义，以及在函数、结构体、枚举、方法中定义使用泛型的方式。

<span id="2"></span>

## 2022-11-04

### 计划

   1、根据计划，继续学习trait和生命周期的知识

   2、争取学完编写自动化测试和构建一个IO项目的知识

### 成果

   1、学习了trait定义，就是相当于接口的概念；实现trait的限制即孤儿规则；以及trait作为参数，和trait bound语法等

   2、学习了引用的生命周期保障；生命周期注解的语法；生命周期省略的三条推断规则；静态生命周期等

   3、学习掌握了编写单元测试用例和集成测试用例的方法；以及相关断言宏，should_panic属性使用方法；了解了如果控制测试的运行方式，运行部分测试，过滤运行多个测试，忽略某些测试等方法。

<span id="2"></span>

## 2022-11-05

### 计划

   1、继续学习未完成的构建一个IO项目章节的知识

   2、争取学完迭代器和闭包的知识

### 成果

   1、跟着书籍完成了构建一个grep小程序的功能，并学习了泛型抽取公共方法、结构体封装、生命周期等具体使用

   2、提交了17道rustlings的题目

   3、迭代器和闭包的知识没有开始。

<span id="2"></span>

## 2022-11-06

### 计划

   1、继续学习迭代器和闭包的知识

   2、做些rustlings题目

### 成果

   1、rustlings做了13道题目

   2、由于周日听了个课，只学习完了闭包的知识。了解了闭包相当于匿名函数，如何定义闭包和带有泛型闭包，以及捕获上下文值的FnOnce、FnMut、Fn等 trait bounds。

<span id="2"></span>

## 2022-11-07

### 计划

   1、学习迭代器章节的知识，争取学完下一章进一步认识Cargo

   2、做些rustlings题目

### 成果

   1、学习了解了Iterator trait和next方法，和一些适配器的用法；以及通过impl Iterator trait创建自定义的迭代器

   2、知道了Cargo发布配置，文档注释///和//!的用法以及创建了creates.io的账号并配置token

   3、了解了Cargo工作空间的使用，以及配置依赖create和install 别人的create

   4、做了rustlings异常处理的题目

<span id="2"></span>

## 2022-11-08

### 计划

   1、学习智能指针的章节内容，争取学完该章节

### 成果

   1、学习了Box<T>类型的智能指针，并用其创建递归类型

   2、学习了Deref trait重载解引用运算符，通过其解引用运算符追踪指针的值，以及Deref的装置转换规则

   3、学习了Drop trait运行清理代码以及Rc<T>引用计算智能指针的使用

## 2022-11-09

### 计划

   1、继续学习智能指针的剩余章节内容，搞明白RefCell<T>内部可变性模式和引用循环、内存泄露的知识

   2、争取学习下章中并发的知识，感觉后面的理解越来越难了。

### 成果

   1、今天由于工作上的事情，耽误了一天，只简单看了RefCell<T>内部可变性的了解

## 2022-11-10

### 计划

   1、继续学习RefCell<T>内部可变性模式和引用循环、内存泄露的知识

### 成果

   1、今天学完了RefCell<T>关于可以改变不可变引用的值，并了解了Rust也存在内存泄露的风险，以及通过弱引用来避免

   2、这章看的比较吃力，晚上又从头看了以便，并完善了学习笔记。

## 2022-11-11

### 计划

   1、计划学完并发章节的知识

   2、争取学习下章面向对象特性的部分内容

### 成果

   1、完成并发章节的学习，使用spawn创建线程；使用channel在线程间传送数据；互斥器Mutex的使用

   2、了解了使用Sync和Send trait进行并发扩展，并且手动实现Send和Sync是不安全的

## 2022-11-12

### 计划

   1、计划学习Rust的面向对象特性

   2、争取学习完模式与模式匹配的章节

### 成果

   1、学习了Rust中对象和封装对应的实现方式，通过trait实现继承以及面向对象的设计模式-状态模式的编写和改进

   2、了解了使用Sync和Send trait进行并发扩展，并且手动实现Send和Sync是不安全的

   3、学习了模式匹配各种方式，match、if let、while let、for、let、函数参数等

   4、知道了可反驳性和不可反驳的模式区别

   5、了解了所有模式的匹配语法，范围匹配、解构分解、忽略和匹配守卫条件等

## 2022-11-13

### 计划

   1、计划学习Rust的高级特征章节内容

   2、做些rustlings题目

### 成果

   1、今天因为上课在职研究生课，时间有限，阅读了一点unsafe的内容，做了16道rustlings题目

## 2022-11-14

### 计划

   1、继续学习Rust的高级特征章节内容

   2、做些rustlings题目

### 成果

   1、今天继续了rustlings4道题目

## 2022-11-15

### 计划

   1、继续学习Rust的高级特征章节内容

### 成果

   1、由于时间有限学习了部分高级trait的内容

## 2022-11-16

### 计划

   1、继续学习Rust的高级特征章节内容

​    2、参加线上resic-v的课

### 成果

   1、晚上有限学习了部分高级类型和高级函数与闭包的内容

   2、了解了宏定义的使用以及宏和函数的不同

   3、参加了线上课程，听了risc-v的基础指令和不同状态的内容

## 2022-11-17

### 计划

   1、继续学习Rust的宏的知识

​    2、做完rustlings题目

### 成果

   1、周四晚上加班，耽搁一晚

## 2022-11-18

### 计划

   1、继续学习Rust的宏的知识

   2、做完rustlings题目

### 成果

   1、学习完了最后章节Rust宏的内容，对于如何编写自定义宏有了初步的任务，但还是很模糊，了解了类属性宏和类函数宏

   2、坐了部分rustlings的题目

## 2022-11-19

### 计划

   1、继续RISC-V课程

   2、做完rustlings题目

### 成果

   1、参加线上课程RISV-V页表的讲解课程

   2、做了部分rustlings的题目，还剩下最后一题

## 2022-11-20

### 计划

   1、继续RISC-V课程

   2、做完最后rustlings题目

### 成果

   1、参加线上课程RISV-V指令的课程

   2、作完了所有rustlings题目

## 2022-11-21

### 计划

   1、由于工作日要上班，抽空看看RISC-V手册和特权指令

### 成果

   1、RISC-V特权指令集阅读17页

## 2022-11-22

### 计划

   1、抽空摸鱼看完RISC-V手册和特权指令

### 成果

   1、看完了解了特权指令的书籍，看的是模模糊糊

​    2、看了RISC-V手册第十章的前5小节内容

## 2022-11-23

### 计划

   1、抽空摸鱼看完剩下的RISC-V手册第10章的内容

### 成果

   1、阅读完毕手册第10章的内容

   2、领取了lab0的实验

## 2022-11-24

### 计划

   1、学习RISC-V基本汇编语言的指令

   2、配置实验环境、准备docker环境安装

### 成果

   1、学习了RISC-V基本汇编指令
   2、配置docker环境安装成功，make docker有问题，mnt目录下没有代码
## 2022-11-25

### 计划

1、学习RISC-V基本汇编语言的指令

### 成果

1、学习了RISC-V第二章和第三章基本汇编指令内容，看的似懂非懂
## 2022-11-26

### 计划

1、继续安装docker环境
2、配置实验0的环境

### 成果

1、本地机器上解决了make docker时没有代码的问题
2、跟着教程配置好了实验环境，正在学习第一章：应用程序与基本执行环境
## 2022-11-27

### 计划

1、继续第一章：应用程序与基本执行环境的学习
2、学习下OS课程slids的内容

### 成果

1、移除标准库依赖跟着文档做了一下，由于缺乏OS的知识，准备先学习下OS的课程

## 2022-11-28

### 计划

1、工作日需要上班，晚上学习第二讲实验介绍的4节内容

### 成果

1、学习完了实验的四节内容，对OS软硬件启动和程序加载执行有了初步的认知。

## 2022-11-29

### 计划

1、工作日需要上班，晚上跟着文档继续学习应用程序与基本执行的内核第一条指令的实践

### 成果

1、由于工作和家庭原因，晚上耽搁了学习实践

## 2022-11-30

### 计划

1、跟着文档继续学习应用程序与基本执行的内核第一条指令的实践

### 成果

1、根据文档指导构建成功了用户态执行环境，并打印出了“Hello,Word”
2、构建裸机执行环境刚开始弄未完成
3、需要针对Rust宏进行深入学习

## 2022-11-31

### 计划

1、晚上跟着文档继续学习应用程序与基本执行的内核第一条指令的实践并完成裸机执行环境的内容学习
2、白天上班时间抽空看下rust宏的文档进行学习宏的编写

### 成果

1、跟着文档学完了内核第一条指令的实践，但还需要完善打印hello word的 rust代码，以及如何重写panic
2、白天工作没有时间看rust宏的内容，该计划暂时搁浅

## 2022-12-01

### 计划

1、晚上继续完善代码，争取靠自己的努力输出实验结果
2、白天上班时间抽空看下rust宏的文档进行学习宏的编写
### 成果

1、进度停止一晚

## 2022-12-02

### 计划

1、晚上继续完善代码，争取靠自己的努力输出实验结果
2、白天上班时间抽空看下rust宏的文档进行学习宏的编写
### 成果

1、晚上看孩子进度停止一晚
## 2022-12-03

### 计划

1、继续完善代码，争取靠自己的努力输出实验结果
### 成果

1、周六帮忙照看孩子，停止一天
## 2022-12-04

### 计划

1、继续完善代码，争取靠自己的努力输出实验结果
### 成果

1、周日参加线上课程，耽误一天
## 2022-12-05

### 计划

1、继续完善代码，争取靠自己的努力输出实验结果
### 成果

1、试着调整了下console的代码，没有打印出结果。明天晚上继续查看rCore-Tutorial教程文档学习，搞清楚原因

## 2022-12-06

### 计划

1、查看rCore-Tutorial教程文档学习，完善代码，争取靠自己的努力输出实验结果
### 成果

1、工作耽搁暂停一晚
## 2022-12-07

### 计划

1、查看rCore-Tutorial教程文档学习，完善代码，争取靠自己的努力输出实验结果
### 成果

1、工作耽搁暂停一晚
## 2022-12-08

### 计划

1、查看rCore-Tutorial教程文档学习，完善代码，争取靠自己的努力输出实验结果
### 成果

1、工作耽搁暂停一晚
## 2022-12-09

### 计划

1、查看rCore-Tutorial教程文档学习，完善代码，争取靠自己的努力输出实验结果
### 成果

1、工作耽搁暂停一晚
## 2022-12-10

### 计划

1、查看rCore-Tutorial教程文档学习，完善代码，争取靠自己的努力输出实验结果
### 成果

1、完成了输出Hello word的代码程序
2、疑问1：调用用户态的ecall为何是64，而M态下的是1
3、疑问2：调用RUSTSBI的内置功能有哪些，为何用户态下的代码不能正常输出

## 2022-12-11

### 计划

1、查看rCore-Tutorial教程文档学习，针对疑问点进行搜索解答
2、进行下一步的实验2
### 成果

1、疑问1：调用用户态的ecall为何是64，而M态下的是1？明白了用户态程序调用的是本地操作系统的系统调用，跟M态下的是不一样的。
2、疑问2：调用RUSTSBI的内置功能有哪些，为何用户态下的代码不能正常输出？查到了RustSBI的creats，看到了相关常量的定义和function
3、进行了实验2的配置
## 2022-12-12
### 计划

1、根据文档进行实验2的学习
### 成果

1、待续……