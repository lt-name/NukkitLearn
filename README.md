# 在阅读本教程前，务必阅读本Readme

目前由官方承认的几个宣传贴

https://www.minebbs.com/threads/dreamserver-nukkit-nukkit.2912/

https://www.mcplugin.cn/thread-1259-1-1.html

https://www.mcbbs.net/forum.php?mod=viewthread&tid=927009

https://www.mcbbs.net/forum.php?mod=viewthread&tid=930861&mobile=2

# 史上最详细的Nukkit教程
#### Learning Nukkit Whoever you are!


- [中文(简体)](README.md)
- [English](README_en.md)

#### 说明

您可以在这里作为一本书观看教程: [http://nl.noyark.net/](http://nl.noyark.net/)

本教程遵循[发现者小组公约](LICENSE)

#### 友情链接

- [NukkitLearn视频讲解](https://search.bilibili.com/all?keyword=BV16z411b7et&from_source=nav_search_new)

#### 关于主要作者

事实上作者上已经退坑了，但是不影响写教程，只是有几点还请悉知:
- 不要问如何搭建服务器；
- 不要PM任何有关人员定制插件；
- 除了写这个教程，作者不会参与任何和Minecraft有关的活动和交易；
- 本教程需要一定的Java基础，请先做好预习功课，并且作者不会回答任何基础的问题；
- 作者目前是高中学生,因此时间并不充裕，更新速度请大家海涵；
- 如有任何疏漏或Bug的存在，还请指正；

#### 作者的扯皮

Nukkit核心作为一个服务端开发框架，虽然性能优越，吸引了大批的开发者加入开发，但教程稀少，学习难度大，使很多小白
望而却步，基于目前很多人对于教程的渴望，包括作者在初学的时候只能通过到处询问和看核心源码来了解如何使用一个东西，
但并不是所有的人都能安心去看核心源码或者到处询问问题。同时，本教程会重复强调一件事情: 打好基础，本教程已经列出
您需要掌握的java基础，什么0基础直接学习nukkit都是骗人的，作者已经见过很多这样的初学者，很少的人通过这种方式
学会(无疑是一种懒散的行为)，nukkit事实上就是学习一个新的api,并无很大的入门难度，只要您学习了基础，就能很快从
这里得到启发，并参与到nukkit的大家庭。

主作者其实很和蔼，但是对于简单的问题作者由于时间问题是不能回答的，也不能干刷屏之类的事情，再和蔼的人也会把你给
屏蔽，当然，作者坚持开放原则，如果有相关问题，可以issues发表您的疑问。

同时，记得给项目一个star支持一下，并且将这个项目宣传给别人，在支持作者同时，造福他人。您的支持和宣传就是作者写下去的动力，
希望这个教程可以帮到您，我们由衷的感谢:)

--- MagicLu550

#### 关于本教程

Nukkit官方说过: Nukkit是一款高性能的核能驱动的Minecraft基岩版服务器,它的
速度更快，性能相比PocketMine更高。
```
Nukkit is nuclear-powered server software for Minecraft Bedrock Edition. It has a few key advantages over other server software:

Written in Java, Nukkit is faster and more stable.
Having a friendly structure, it's easy to contribute to Nukkit's development and rewrite plugins from other platforms into Nukkit plugins.
Nukkit is under improvement yet, we welcome contributions.
```

目前，依托Java语言的健壮性,Nukkit形成了强大的生态，并且出现了很多分支，目前使用最广泛的分支是[NukkitX](http://nukkitx.com)

感谢您能观看我们编写的教程。该教程在编写阶段，更新间隔可能会很长。
请谅解。该教程是为了简化目前很多晦涩难懂的教程，使得有过Java语法基础的朋友
能方便地了解Nukkit和学习Nukkit. 目前Nukkit的学习难度主要在于其资料过少。
我们将会整理和参考其他相关资料来编写该教程，也感谢您参与编写，造福大家

同时，转发本教程应当附上GitHub原地址，不得任意转发和搬运，以及商业使用。
本教程不涉及语法，只涉及Nukkit的各种库的解释以便于开发

基础推荐学习的地方

- [菜鸟教程](https://www.runoob.com/java/java-tutorial.html?tdsourcetag=s_pcqq_aiomsg)
- [w3cschool](https://www.w3cschool.cn/java/java-tutorial.html)
- [并发](https://blog.csdn.net/likun557/article/details/100148245)
- [网络](https://www.cnblogs.com/cainiao-chuanqi/p/11338202.html#autoid-3-2-0)

您所需要掌握的最基本的Java基础体系
```
  --基础部分
    -- 语法
      -- 变量定义
      -- 方法定义
      -- 基本表达式
        -- 逻辑表达式
        -- 算数表达式
      -- 流程控制
        -- 条件语句
        -- 循环语句
        -- 选择语句
    -- 面向对象
      -- 类，对象的概念
      -- 定义类和声明对象
      -- 包的概念
      -- 匿名内部类
      -- 接口
      -- 抽象类，抽象方法
      -- lambda表达式
      -- 面向对象的三大特征
        -- 继承
        -- 封装
        -- 多态
      -- 枚举
      -- 注解
   -- 类库
      -- 反射
      -- 多线程
      -- 字符串操作
      -- 数字包装类
      -- io流
        -- bio
        -- nio
      -- 套接字Socket
        -- udp
        -- tcp
      -- 时间类库
      -- 系统类库

```
未来，我们会开发Nukkit-d,是对于Nukkit设计思想的整理和重新实现，以解决目前nukkit维护难的问题
#### 关于我们

如果您有兴趣可以随时发送Pr等
本教程不定期更新，大概寒假时期更新最快
相关意见可以联系843983728@qq.com或者加QQ:843983728

QQ群: 931210534

![QQ群](images/0-00.png)

#### 贡献标准和须知

1. 教程要求尽量自然，易懂，符合本项目所追求的"人人可以学习Nukkit"的宗旨
2. 编写教程可以在参与编写者添加自己的名字，若没有可以自己手动加入，如第一章所同
3. 照搬其他教程原文需要得到作者同意，并且在下面注明参考文献。
4. 若发现侵权行为，与本项目领导者无关，但我们会积极配合找到侵权者
5. 请尽量以第一章为范本编写您的内容。
6. 如果有知识缺点，请在Readme里注明这个缺点出处，写在知识缺点里,知识缺点在章节中标注。
7. 教程补充首要的是解决知识缺点
8. 由于编写人数较少,教程不避免的会有错误，漏洞，不严谨，如果发现，可以发送pullRequest参与修改

#### 知识缺点:
   - 关于fallBackPrefix的作用 - 第二章和第四章 [1]

#### 专栏

   - [填坑专栏](专栏-关于我们常见的那些坑.md)
   
   - [用指令设置玩家实体大小](章外篇/章外篇之一-用指令设置玩家实体大小(简单版).md)

   - [多语言解决方案](章外篇/章外篇之二-多语言解决方案.md)
   
   - [使用groovy编写插件](章外篇/章外篇之三-使用groovy编写您的项目.md)
   
   - [使用DSL编写配置文件](章外篇/章外篇之四-使用DSL编写您的静态配置文件.md)

   - [常用工具](章外篇/索引-常用工具的网页索引.md)
#### 目录
- [第一章 基础准备](第一章/1-0_前言.md)
  - [X] [如何搭建开发环境](第一章/1-1_如何搭建环境.md)
  - [X] [插件要素](第一章/1-2_插件要素.md)
  - [X] [如何编写监听器](第一章/1-3_如何编写监听器.md)
  - [X] [如何编写指令](第一章/1-4_如何编写命令.md)
  - [X] [如何使用配置文件](第一章/1-5_如何使用配置文件.md)
  - [X] [如何编写plugin.yml](第一章/1-6_如何编写plugin.yml.md)
  - [X] [PluginBase类](第一章/1-7_PluginBase类.md)
  - [X] [练习案例](第一章/1-8_案例玩家进入信息等效果.md)
- [第二章 nukkit的工具和各种事件介绍](第二章/2-0_前言.md)
  - [X] [主要的事件的介绍](第二章/2-1_主要的事件介绍.md)
  - [X] [事件相关方法](第二章/2-2_事件相关方法.md)
  - [X] [计时器的介绍](第二章/2-3_计时器的介绍.md)
  - [X] [Server类和PluginManager类](第二章/2-4_Server类和PluginManager类.md) 
  - [ ] [各种实体类的方法介绍](第二章/2-5_各种实体类的方法介绍.md)
  - [ ] [各种工具类的介绍](第二章/2-6_各种工具类的介绍.md)
  - [X] [如何发送数据包](第二章/2-7_如何发送数据包.md)
- [第三章 nukkit的UI操作](第三章/3-0_前言.md)
  - [X] [主要的Form种类及介绍](第三章/3-1_主要的Form种类及介绍.md)
  - [X] [使用NukkitX自带的Form创建UI](第三章/3-2_使用NukkitX自带的Form创建UI.md)
  - [X] [使用外部库GUI创建UI](第三章/3-2_使用外部库GUI创建UI.md)
- 第四章 nukkit实用操作
  - [ ] 粒子
  - [ ] 药水
  - [ ] 坐标计算
  - [ ] AI寻路计算
  - [ ] 加自定义块自定义实体区块生成
  - [ ] 皮革染色
  - [ ] NBT的使用方式
  - [ ] 客户端的联动
  - [ ] 自定义数据包
- 第五章 nukkit相关实例
- 第六章 nukkit原理剖析


#### 专栏状况
```diff
+ 专题
+ 提示信息
```
