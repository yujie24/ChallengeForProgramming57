# 挑战编程技能：57道程序员功力测试题

Exercises for Programmers by Brian P.Hogan

<div align=center>
  <img src="https://github.com/yujie24/ChallengeForProgramming57/blob/master/Exercises%20for%20Programmers.jpg" width=40% height=40% alt="Figure 1.English Cover"/>
  <img src="https://github.com/yujie24/57_Challenges_For_Coding_Skills/blob/master/%E6%8C%91%E6%88%98%E7%BC%96%E7%A8%8B%E6%8A%80%E8%83%BD-57%E9%81%93%E7%A8%8B%E5%BA%8F%E5%91%98%E5%8A%9F%E5%8A%9B%E6%B5%8B%E8%AF%95%E9%A2%98.jpg?raw=true" width=41.5% height=41.5% alt="Figure 2.中文封面"/>
</div>

> When you write software, you need to be at the top of your game. Great programmers practice to keep their skills sharp. Get sharp and stay sharp with more than fifty practice exercises rooted in real-world scenarios. If you’re a new programmer, these challenges will help you learn what you need to break into the field, and if you’re a seasoned pro, you can use these exercises to learn that hot new language for your next gig.


**这是一本通用于提高所有语言、所有程序员的编程技能的书，一共列举了九个章节共57个问题。对于提高编程能力，训练编程思维来说，我认为确实很有用处。

**说明：书中并没有教读者具体的代码，也没有指定具体某一种编程语言，而是教会大家编程的思维与能力。所以不论是C还是java，或者是我所用的python，都阔以使用。欢迎补充！**


# 目录

|章   节|问   题|
|------|-------|
|第一章 将问题转变成代码|理解问题|
||发现输入、处理和输出|
||用测试驱动设计|
||用伪代码编写算法|
||挑战|
||前进|
|第二章 输入、处理和输出|题1 问好|
||题2 计算字符数|
||题3 打印引语|
||题4 疯狂填词|
||题5 简单的数学处理|
||题6 计算退休时间|
|第三章 计 算|题7 矩形房间的面积|
||题8 比萨聚会|
||题9 涂料计算程序|
||题10 自助结账|
||题11 货币兑换|
||题12 计算单利|
||题13 确定复利|
|第四章 做出决策|题14 税额计算程序|
||题15 密码验证|
||题16 法定驾驶年龄|
||题17 计算血液中的酒精含量|
||题18 温度转换程序|
||题19 计算身高体重指数|
||题20 多州税收计算程序|
||题21 从数字到名字|
||题22 比较数字|
||题23 定位汽车问题|
|第五章 函 数|题24 字母易位词检查程序|
||题25 检查密码强度|
||题26 计算还清信用卡欠款所需的时间|
||题27 验证输入|
|第六章 重 复|题28 数字相加|
||题29 处理错误的输入|
||题30 乘法表|
||题31 卡蒙内心律|
||题32 猜数字游戏|
|第七章 数据结构|题33 神器8号球|
||题34 。。。。|


# 第一章   将问题转变成代码

### 理解问题

### 发现输入、处理和输出

### 用测试驱动设计

### 用伪代码编写算法

### 挑战

### 前进

# 第二章   输入、处理和输出

### 题1 问好

创建一个提示输入名字并打印包含该名字的问候信息的程序。

示例输出：

> What is your name? Brian

> Hello, Brian, nice to meet you!

约束：

- 输入、字符串连接、输出，这几部分要分开。

代码：

```python

name = input("What is your name?")

print("Hello,",name+",","nice to meet you!")

```

挑战：

- 不使用任何变量，编写一个新版本的程序。

- 编写一个新版本，对不同的人显示不同的问候语。在完成第4章和第7章的练习后，这是个值得一试的不错的挑战。

### 题2 计算字符数

创建一个程序，提示用户输入字符串，然后输出这个字符串，以及其中包含的字符数。

示例输出：

> What is the input string? Homer

> Homer has 5 characters.

代码Python：

```python

str = input("What is the input string?")
print(str,"has", len(str),"characters.")

```

约束：

- 确保输出中包含原始的字符串。

- 使用一个输出语句来构造输出。

- 使用所用编程语言中的一个内置函数来确定字符串的长度。

挑战：

- 如果用户什么都没输入，提示用户输入内容。

- 使用图形用户界面实现该程序，在每次键盘按下时，更新字符计数信息。如果所用语言没有特别友好的GUI库，尝试使用HTML和JavaScript来做这个练习。

### 题3 打印引语

创建一个程序，提示用户输入一条引语及其作者。按照示例输出那样显示引语和作者。

示例输出：

>What is the quote? These aren't the droids you're looking for.

>Who said it? Obi-Wan Kenobi

>Obi-Wan Kenobi says, "These aren't the droids you're looking for."

约束：

- 使用一条输出语句来生成该输出，使用适当的字符串转义技术来处理引语。

- 如果所用编程语言支持字符串插入或替换，在这个练习中不要使用。要使用字符串连接。

代码Python:

```python

quote = input("What is the quote?")
people = input("Who said it?")
print(people,"says,","\""+quote+"\"")

```

挑战：

- 在第7章中，你将练习使用数据的列表。修改这个程序，不再提示用户输入引语，而是自己创建一个保存引语及其作者的结构，然后使用例子中的格式显示所有的引语。由映射（map）组成的数组会是个不错的选择。

### 题4 疯狂填词

创建一个简单的疯狂填词程序，提示用户输入一个名词、一个动词、一个形容词和一个副词，然后将这些词插入到所创建的故事中。

示例输出：

> Enter a noun: dog

> Enter a verb: walk

> Enter an adjective: blue

> Enter an adverb: quickly

> Do you walk your blue dog quickly? That's hilarious!

约束：

- 在程序中使用一条输出语句。

- 如果所用语言支持字符串插入或替换，则使用它来构造输出。

挑战：

- 向程序中添加更多输入，扩展故事。

- 实现一个带有分支发展的故事，可以根据问题的答案来确定如何构造故事。在第4章的问题中，你将进一步探索这个概念。

### 题5 简单的数学处理

### 题6 计算退休时间


# 第三章   计算

### 题7 矩形房间的面积

### 题8 比萨聚会

### 题9 涂料计算程序

### 题10 自助结账

### 题11 货币兑换

### 题12 计算单利

### 题13 确定复利

# 第四章   做出决策

### 题14 税额计算程序

### 题15 密码验证

### 题16 法定驾驶年龄

### 题17 计算血液中的酒精含量

### 题18 温度转换程序

### 题19 计算身高体重指数

### 题20 多州税收计算程序

### 题21 从数字到名字

### 题22 比较数字

### 题23 定位汽车问题

