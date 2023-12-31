---
title: 《程序员数学 v2.0》
lock: need
---

# 《程序员数学 v2.0》

作者：小傅哥
<br/>博客：[https://bugstack.cn](https://bugstack.cn)

> 沉淀、分享、成长，让自己和他人都能有所收获！😄

在我还是初级程序员时，每天也都粘贴着代码和包装着接口。那个阶段并没有意识到数学能在编程中起到什么作用，就算学了数学的部分知识，也没法用到编程中。但后来随着编程越来越久，逐步接手核心代码块开发时候，用到的数学越来越多了。包括：开发的规则引擎用到的B-自平衡二叉树、数据库路散列算法用**雪崩测试**论证了不同散列算法的使用情况、要处理非对称加密数学时验证了素数的合理选择。直到这时候越来的发现，不是知识`没用`，而是因为你`没用`到。

为了让更多的伙伴可以夯实数学基础，提升自身编程思想。小傅哥的 **《程序员数学 v2.0》** PDF 22年编写完成了，今天分享给在座的各位兄弟。

## 一、前言：谷歌招聘

**2004年**，在硅谷的交通动脉 101 公路上突然出现一块巨大的广告牌，上面是一道数学题：`{e 的连续数字中最先出现的 10 位质数}`.com。

<div align="center">
    <img src="https://bugstack.cn/assets/images/2020/all-20-1.png" width="500px">
</div>

广告：这里的 e 是数学常数，自然对数的底数，无限不循环小数。这道题的意思就是，找出 e 中最先出现的 10 位质数，然后可以得出一个网址。进入这个网址会看到 Google 为你出的第二道数学题，成功解锁这步 Google 会告诉你，`我们或许是”志同道合“的人`，你可以将简历发到这个邮箱，我们一起做点改变世界的事情。

*计算 e 值可以通过泰勒公式推导出来：e^x≈1 + x + x^2/2! + x^3/3! +……+ x^n/n! (1) 推导计算过程还包括`埃拉托色尼筛选法(the Sieve of Eratosthenes)`、`线性筛选法`的使用。感兴趣的小伙伴可以用代码实现下。*

除了谷歌以外；
- Facebook 在面试时问过：“如何在一个有向图中找到最短路径“
- Amazon 在面试时问过：“如何在一个有向图中找到最短路径”
- Microsoft 在面时问过：“如何在一个有向图中找到环”
- Apple 在面试时问过：“在一个无向图中找到最短路径”

国内的互联网也喜欢问能不能手写一个红黑树，但现在逐步升级了，从真实场景中考察你对算法运用到实际场景中的能力。比如：你运用过什么算法优化布隆过滤器的哈希碰撞、你的数据库路由算法雪崩测试如何验证的、抽奖生成x个用户生成n个抽奖码最后如何快速结算。

**经过这么多，我想说**：“不提升数学方面的知识积累，编程能力只能停留在初级阶段。”

## 二、新书：提升数学

《程序员数学 v2.0》是小傅哥关于整理编程`数据结构和算法`方面的书籍资料，本书为结合数据结构14篇继续扩展关于数学的14篇内容。如包括；`“如何使用二进制计算乘法？”`、`“为什么不能用斐波那契散列，做数据库路由算法？”`、`“素数用途 - RSA 加密算法解析”`、`“杨辉三角的数学逻辑特点”`等内容。

有数学才有编程之美，代码是对数学逻辑的具体实现，有了数学支撑才让编程逻辑具有灵魂。而小傅哥也希望每一个程序员都能积累这些数学知识，如：扰动函数、负载因子、斐波那契（Fibonacci）、欧拉公式、贝祖定理、线性同于方程、中国余数定理、费马小定理等。

<div align="center">
    <img src="https://bugstack.cn/images/article/zsxq/pdf-maths-02.png" width="650px">
</div>

书籍下载：关注公众号【`bugstack虫洞栈`】回复【`程序员数学`】

**Hello, world of programmer mathematics！** 你好，程序员数学的世界！

欢迎来到这里，很高兴你能拿到这本书。如果你能坚持看完书中每章节的内容，那么不仅可以在你的面试求职上有所帮助，也更能让你对关于程序员数学方面的知识有更加深入的学习。

**《程序员数学》** 是一本通过 Java 语言渐进式的讲解数据结构的书籍，通过循序渐进的方式介绍程序员数学方面的知识。全书共计 5 章 28 节，268 页 6.9 万字 200+张图片，耗时 6 个月完成。涵盖 4 类 14 种数据结构，包括：链表、数组、队列、堆栈、哈希表、堆、字典树、二分 搜索树、平衡二叉树、2-3 树、红黑树、并查集、图、布隆过滤器，以及数学部 分 14 章，包括:二进制、阶乘、斐波那契、RSA、割圆术、傅立叶变换等，后续还会继续扩充。`下一次就是v3.0版本了`。

### 1. 适合人群

1. 具备基本编程技能，在校大学生和工作的研发人员
2. 对数据结构和算法感兴趣，但总感觉看不懂的
3. 看了太多理论，但没有实践验证的
4. 求职面试，总被面试题搞的死去活来的

### 2. 阅读建议

本书虽然是源码分析、理论实践，但并不会让读者感觉枯燥。作者：`小傅哥`，在每一篇的知识里都通过对数据结构的实践和配图来讲解。小伙伴在阅读的时候可以对照源码实践，并且在源码中还包括了一些必备的原图稿件方便做笔记。希望这本书彻底教会你数据结构，也让所有**认真阅读的读者**，学习后都能`让懂了就是真的懂`！

---

好啦，这是新年前的最后一本PDF啦。**每一本原创资料的PDF输出，都要在1~3个月甚至半年时间；整理资料、编写文章、开发代码，再到PDF的封面的设计和内容的归纳。** 也因此希望读者伙伴可以在获取资料的同时，**留言**、**分享**、**点赞**支持，我非常需要你的帮忙！非常感谢！
