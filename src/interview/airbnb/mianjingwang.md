电面： nested iterator, follow-up: remove function

onsite:

1. boggle game, 但是呢比如你现在走了一个词apple, 那么a, p, p, l, e这几个char的位置不能继续用了。于是给你一个board, 一个dict让你计算最多能有多少个valid单词出现在这个Board上面

2.
john’s travel city: a1 a2 c2 h8 j9
tom’s travel city: b1 a1 c3 z5
kate travel city: a2 a1 h8 x8

给你一个人john, 以及他的一堆朋友，让你计算出来和他travel的city相似度大于75%的所有朋友，并且根据这个相似度对朋友排序

3. 给一组meetings（每个meeting由start和end时间组成）。求出在所有输入meeting时间段内没有会议，也就是空闲的时间段。
每个subarray都已经sort好
举例：
[
[[1, 3], [6, 7]],
[[2, 4]],
[[2, 3], [9, 12]]
]
返回
[[4, 6], [7, 9]]

4. behavior: 要表现爱bnb

5. behavior: 要表现爱bnb

饭不是很好吃，最后被拒。

补充内容 (2015-12-9 15:25):
那个第一题，我现在还没明白怎么做才是对的。第二题应该是要倒排索引。


首先是三个技术面：
1） Alien Dictionary
2） Text Justification
3） 写echo TCP client， 向面试官的server发请求， 读回数据。地里比较少人说这种， 我来详细说一下， 情境是这样的： 想象你开车， 踩下油门，车会加速，放开油门，车会减速。 client向server发的请求有以下2种： （a）STATUS –表示查询现在车的速度和踩下踏板的压力； （b）THROTTLE 50.1 — 这条指令是“THROTTLE” 加上一个数字， 表示我现在将踩油门的压力调为50.1

EXAMPLE: 比如在telnet中
STATUS
0.0 0.0 (这行是server返回的， 第一个数字表示压力，第二个数字表示速度)
THROTTLE 50.1 (这个指令发出 server没有返回)
STATUS
50.1 3.75 (可以看到速度在缓慢上升)
STATUS (过几秒后，你又发STATUS指令过去)
50.1 15.98 (速度依旧上升。。。)

对就是这样，像是简单物理实验。

写完TCP client后，要求是写一个方法将速度控制到达一个target speed

最后一个问题是求这个 delta力 和 delta速度 之间的函数关系。。。。。。。。醉了。我物理还给老师了。。。。。。时间不够了

希望可以帮助到大家！！！

补充内容 (2016-1-14 00:55):
补充一下core value面：
1）what bring you to airbnb?
2) what can you teach your co-workers after you get in?
3) describe a person whom you admire most
4) describe your experience with airbnb

补充内容 (2016-1-14 00:55):
5) where have you been to?
6) what will you do if you win a lottery such as Powerball?
7) what is the biggest fear in your life?
8) how do describe Airbnb to a people back to 2003?

补充内容 (2016-1-14 00:56):
9) if you have a book that writes about your whole life, will you read it? why?
10) if you have a time machine, and you can either go back or go forth, will you choose to go back or to go forth?

补充内容 (2016-1-14 00:56):
11) among all the features of airbnb, what do you want to improve?

补充内容 (2016-1-14 00:57):
就这么多了~想起来再加~大家觉得有用就给我加米哈

补充内容 (2016-1-14 12:59):
12) 描述一件你当时觉得非常risky的事情，你是怎么做的，结果如何



1. 2D array, 访问顺序必须是‘回’字的方式，就是从外圈转到里圈，写出class,
Iterator, hasNext(), next().
2. 电话号码和计费的一个log, 去parse 看规定时间内哪个号码产生费用最高。
3. leetcode anagram 的一题变种
4. 有很多个sorted queue存在不同服务器上，如何有效的读取到一个 sorted 大queue
里 (google也面到了这题）
5. 设计db, 如何存取房东和房客的reviews, 如何maintain他们之间的关系。

Airbnb确实和大家说得一样面试官很nice, 内部装潢笔格明显很高，非常酷炫.
offer: 160k + 5000股／2年 ＝ 260k


考的是一道面经题：palindrome pair
我先说了brute force的算法，然后小哥问怎么improve，我就想了一下说了check pre and post fix的方法，然后写了code,最后run test case也过了，小哥说很不错，可是还是不知道为什么悲剧了。。。


1. 2D array, 访问顺序必须是‘回’字的方式，就是从外圈转到里圈，写出class,
Iterator, hasNext(), next().
2. 电话号码和计费的一个log, 去parse 看规定时间内哪个号码产生费用最高。
3. leetcode anagram 的一题变种
4. 有很多个sorted queue存在不同服务器上，如何有效的读取到一个 sorted 大queue
里 (google也面到了这题）
5. 设计db, 如何存取房东和房客的reviews, 如何maintain他们之间的关系。

