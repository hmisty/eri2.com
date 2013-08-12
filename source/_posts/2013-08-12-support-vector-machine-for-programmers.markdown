---
layout: post
title: "Support Vector Machine For Programmers"
date: 2013-08-12 23:01
comments: true
categories: data
---

# SVM For Programmers, part 1

*Mathematicians read formulas. Programmers read codes. Perl Monks read $#&^\_@!. -- Evan*

Hence I decided to summarize a completely painless tutorial of SVM (Support Vector Machine) for programmers and let codes talk.

Even though I found out very good [lecture notes by Andrew Ng for CS229][1], comprehensive and wonderful [presentation by Alexander Statnikov et al][2], and someone's even similar idea [the machine learning for hackers][3] where chapter 12 is about SVM.

For whom wants to DIY or hack SVM.

Here we start.

## Prerequisite

In this tutorial, we will still need to do some math. But don't worry. High school math plus a little bit calculus and linear algebra would be just fine.

More importantly, I will use three different programming languages to show you the coding implementations which are R, clojure and python. If you have not yet been familiar with the three fabulous tools, here are some nice resources for you to catch up:

* learning R: [A (very) short intro to R][4] (pdf); [Try R at Code School][5] (online learning)
* learning clojure: [Clojure learning resources][6] (web page); [4clojure][7] (online learning)
* learning python: [Learn Python the Hard Way][8] (free book); [python at codeacademy][9] (online learning)

******

# SVM For Programmers, part 1 (Chinese)

*数学家读公式。程序员读代码。Perl程序员读$#&^\_@!。-- Evan*

因此我决定总结一篇关于SVM（支持向量机）的指南。用代码讲述。

尽管我发现了[Andrew Ng的CS229课程的出色教案][1]、[Alexander Statnikov等内容丰富精彩的讲义][2]以及一本具有类似构思的书[《黑客的机器学习书》][3]————在书的第12章讲到了SVM。

为了那些想DIY或hack SVM的同学。

就此开始。

## 预备知识

在这篇指南中，我们仍然需要做一点点的数学演算。不过不用担心。高中数学加上一点微积分和线性代数知识就足够了。

更重要的，我会使用三种不同的编程语言来讲述算法的代码实现：R、clojure和python。如果你尚不熟悉这三种极好的工具，这里是一些学习的资源：

* 学习R：[A (very) short intro to R][4] (pdf); [Try R at Code School][5] (online learning)
* 学习clojure：[Clojure learning resources][6] (web page); [4clojure][7] (online learning)
* 学习python：[Learn Python the Hard Way][8] (free book); [python at codeacademy][9] (online learning)


[1]: http://219.239.26.20/download/37689091/52516876/5/pdf/230/39/1361316241894_807/cs229-notes3.pdf
[2]: http://www.nyuinformatics.org/downloads/supplements/SVM_Tutorial_2010/Final_WB.pdf
[3]: http://www.clayford.net/statistics/machine-learning-for-hackers-chapter-12/
[4]: http://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf
[5]: http://tryr.codeschool.com
[6]: http://readwrite.com/2011/07/01/free-e-books-on-clojure
[7]: http://www.4clojure.com/
[8]: http://learnpythonthehardway.org/
[9]: http://www.codecademy.com/tracks/python

