# 我不是技术岗，只是学了点编程

## 个人介绍

- 刘娟娟

- 1984 年生

- GitHub: [@liujuanjuan1984](https://github.com/liujuanjuan1984)

- PRESSone: [行动的女巨人](https://press.one/main/p/ed73e900e209def08ff03a2e3fadbac99af087c0)

- 10 年游戏行业从业经历，先后服务过网易、4399、三七互娱等

- 2017 年中开始关注区块链，于2018年初主动离开游戏行业拥抱区块链行业

- 2018 年 3 月创建 PRS 拓荒者社群，半年后加入 PRESSone BD运营团队

## 我的体悟

首次读《自学是门手艺》时，我手痒痒，偷时间用 vscode + git 练习，一坐就是两三个小时，如此沉迷几次，玩出来一个自动处理时间开销数据的脚本，顺便把我们团队用来面试程序员的一道 python 题给做了。看了我的代码后，工程师打趣说：你可以来上班了；另一位也颇为乐意鼓励我说：面试时写出这样的代码确实可以考虑招进来。额…… 我代码读得少，莫哄我转岗。
首次读《自学是门手艺》时，我手痒痒，偷时间用 vscode + git 练习，一坐就是两三个小时，如此沉迷几次，玩出来一个自动处理时间开销数据的脚本，顺便把我们团队用来面试程序员的一道 python 题给做了。看了我的代码后，工程师打趣说：你可以来上班了；另一位也颇为乐意鼓励我说：面试时写出这样的代码确实可以考虑招进来。额…… 我代码读得少，莫哄我转岗。

我是一名运营，不是程序员，没有相关的教育或培训经历。2003 年大一首次接触电脑并只必修了 C 语言。2009 年在网易当QC，主程帮我破冰了很多小到不能再小的知识点，让我学会 linux shell 命令行和 mysql 操作，得以独立胜任在无任何游戏界面的情况下完成游戏战斗系统与合服功能的测试。2011 年在网易内部转岗做策划，主程给我找了一本 python 简明教程，我用一个上午浏览语法规则和全书框架，下午就直接读项目的任务系统脚本，并把代码逻辑转换到 excel 中配表。三个月内，我在搜索引擎和简明教程的帮助下，写了几个子类、一些函数以及很多个游戏脚本，其中包括复杂的场景剧情逻辑。这些代码在主程的把关之下全部提交到项目库并正式上线。这两段职场经历中，我都是拿到就用，边做边学。

与立志通过自学成为专职的程序员的人不同，我喜欢编程，但尚未想过把它变成职业。单凭兴趣，我还有两段编程学习经历，一次是 2016 年底刚生二宝，参加新生大学 js 入门课，只是因产后上班颇为辛苦而中断。另一次就是《自学是门手艺》。

我是如何使用《自学是门手艺》这本书，如何完成了让大家打趣我水平确实不错的代码呢？8年前的那三个月用中学的经历或许让我有些常识和印象，但早已模糊。思来想去，大概是因为：我不善于 coding 但善于拆解需求和迭代代码，我不喜欢硬记于是总是用 google 找答案，且总是把《自学是门手艺》和其它参考书放在手边备查。

《自学是门手艺》这本书的使用方法是，先囫囵吞枣，其后多次细细咀嚼。部分章节用于自我激励与充能，部分章节用于纲领性地建立起一个编程知识框架。编程不复杂，老师一句话就概括起来一个非常健壮的框架线条：

> 从结构上来看，一切的计算机程序，都由且只由两个最基本的成分构成：
> - 运算（Evaluatation）、
> - 流程控制（Control Flow）。

我初步掌握编程的方法也并没有超出老师所强调的：练习、拆解、搜索这3条。以我的实践经验来看，这3条也并非孤立，而是同时存在、互相促进。下面以一道简单的题目为例，展示一下我作为初学者是如何以此为契机练习的：

> 在给出的某篇文章（一份txt文件），统计所有字符的出现次数，并按照次数倒序输出。

原始需求经横向初步拆解后，变成：
- 需求 1.统计次数，
- 需求 2.按照次数倒序。

需求1又该如何继续横向拆解呢？统计1个字符的出现次数，与统计所有字符的出现次数，后者仅仅是在前者的基础上的一个循环处理。于是就继续拆解为：

- 需求 1.1 如何统计某个字符的出现次数
- 需求 1.2 一共需要统计哪些字符？

如果问题复杂，超出了自己的理解范畴，我就降低问题的复杂程度，然后先写代码实现那个简化版的需求。比如需求 1.1 经纵向拆解后，难度从低到高可以转变为：

- 需求 1.1.1 统计一个字符串中某个字符出现的次数
- 需求 1.1.2 统计一个列表中某个字符出现的次数
- 需求 1.1.3 统计一个文件中某个字符出现的次数

对于初学者来说，文件比列表复杂，列表比字符串复杂，但字符串是基础功。如何处理字符串，初学者能立马通过书本和教程 get 到。虽说文件复杂，但其实一点也不复杂。通过搜索或阅读，你很快就会知道 file.readlines() 可以读取文件返回一个列表，for 循环可以依序处理列表中的每一项，由此打通文件→列表→字符串的路径。

并非每次都拆解到基础功，我拆解到自己能掌握的粒度，就开始写代码并运行调试；等这块逻辑通顺了，就写另一块。过程中肯定会遇到困难，我就直接 google 解决办法。带着问题去检索、找到答案、问题解决的这个美妙循环，总是令我一旦编程就停不下来。正因为自己被某个知识点难住，在重读书本的过程中，常常有找到答案的惊喜之感。

编程作为一个专业领域，会有很多专有名词。通读《自学是门手艺》全书，熟悉最少必要的专有名词，就能知道大家一般如何称呼，如此将提高准确描述问题的能力并提高检索效率。其实，就连熟悉专有名词这件事，我都不是硬着头皮记忆的。我的专有名词记忆能力实在是差劲，于是我总是把书在手边随时备查，多搜几次就熟悉了。

通过练习搜索来精通搜索，通过练习编程来掌握编程。确实没什么新鲜秘诀。

这就是我作为一个运营，编程初心者的切身经历。

---

本文的 [PRESS.one 签名](https://press.one/file/v?s=b54fadaeaa3f6dd3f1fb9eedc1a142b91f7b3271b2b81e2141d5243b49e6139531ad25694e973b22b1b9e6427b9adc4692d78604d7018d12d998d8719a551ea20&h=70e40ae7bfcdf876bade2b9c0c0174a6be8ed86fc47a11439270c65585a7ca09&a=ed73e900e209def08ff03a2e3fadbac99af087c0&f=P1&v=3)。

另附：我当时写出来的代码。现在你或许还不会写码，但其实大致能读懂；更或者，你有更好的写法。

```python

import os
import os.path

"""
题目：
文章统计所有字符的出现次数，并按照次数倒序输出

"""

testFile ='D:/myfilepath/text_001.txt'

def main():
    with open(testFile,'rt',encoding='UTF-8') as f:
        blines = f.readlines()

    aList = get_chars(blines)
    muchtimesDic = count_chars(aList,blines)

    keys = muchtimesDic.keys()
    vals = muchtimesDic.values()
    rlist = [(key,val) for key,val in zip(keys,vals)]

    Rlist = sorted(rlist,key = lambda x:x[1],reverse = True)
    for i in Rlist:
        print(i[0],i[1])
    print(Rlist)

def get_chars(blines):
    """
    功能：获取待检索的字符列表。通过遍历文本，把所有出现的字符列举出来。（大小写不敏感）
    """
    aList = []

    for aline in blines:
        aline = aline.lower()
        bline = aline[:]
        for i in bline:
            if i not in aList :
                aList.append(i)
    return aList

def count_chars(aList,blines):
    """
    功能：统计字符出现的次数，并返回字典。
    """
    muchtimesDic = {}

    for i in aList:
        howmanytimes = 0
        for aline in blines:
            aline = aline.lower()
            bline = aline[:]
            if i in bline:
                howmanytimes = bline.count(i) + howmanytimes
        muchtimesDic[i] = howmanytimes
    return muchtimesDic

main()

```