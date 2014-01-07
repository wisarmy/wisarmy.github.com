---
layout: post
title:  "Markdown syntax"
date:   2013-12-02 15:43:08
categories: file update
---

##使用html区块##
    1. 前后加空行
    2. html区块markdown格式语法不会被处理
##标题
####Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。

#####类 Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题），例如：

    This is an H1
    =============

    This is an H2
    -------------
#####任何数量的 = 和 - 都可以有效果。

类 Atx 形式则是在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶，例如：

    # 这是 H1

    ## 这是 H2

    ###### 这是 H6
#####你可以选择性地「闭合」类 atx                             样式的标题，这纯粹只是美观用的，若是觉得这样看起来比较舒适，你就可以在行尾加上     #，而行尾的 # 数量也不用和开头一样（行首的井字符数量决定标题的阶数）：

    # 这是 H1 #

    ## 这是 H2 ##

    ### 这是 H3 ######
##区块引用
>Markdown 标记区块引用是使用类似 email 中用 > 的引用方式。如果你还熟悉在 email 信件中的引言部分，你就知道怎么在 Markdown 文件中建立一个区块引用，那会看起来像是你自己先断好行，然后在每行的最前面加上 > 也允许你偷懒只在整个段落的第一行最前面加上 >
>>区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 >
引用的区块内也可以使用其他的 Markdown 语法,包括标题、列表、代码区块等
## 列表
有序列表

    1. xx
    2. xx
    3. xx

无序列表

    * xx or
    - xx or
    + xx 
## 代码区块
    使用4个空格或一个制表符
## 分割线
    * * *

    ***
    
    *****
    
    - - -
    
    ---------------------------------------
- --------------------------------------------------------------------------------------

##链接
    This is wisarmy's blog [wisarmy](http://github.com/wisarmy/ "wisarmy's github") inline link.
    
#### reference a defined link

    [wisarmyblog]: http://wisarmy.github.com "wisarmy's github"
    
    This is wisarmy's blog [wisarmy] [wisarmyblog]
    
*This is wisarmy's blog [wisarmy][wisarmyblog]*

#### 隐式链接
    [google]: http://google.com
    [google][]
    

*隐式链接标记功能 [google][]*

[wisarmyblog]: http://wisarmy.github.com "wisarmy's github"   
[google]: http://google.com
[wisarmy]: http://github.com/wisarmy


## 强调
    *我是一个小花猫*

    _我是一个小花猫_
    
    **我是一个小花猫**
    
    __我是一个小花猫__

*我是一个小花猫*

_我是一个小花猫_

**我是一个小花猫**

__我是一个小花猫__


- --------------------------------------------------------------------------------------

## 代码

如果要标记一小段行内代码，你可以用反引号把它包起来（`）

    Use the `printf()` function.
如果代码段内要使用`,可以使用两个`` ``包括代码段

    Use the ``printf(`)`` function.

Use the ``printf(`)`` function.

- --------------------------------------------------------------------------------------
## 图片
    像链接形式一样 ![Alt text](/path/to/img.jpg "Optional title")
![ALT text](/assets/luffy.jpg "luffy")

## 自动链接
    <http://google.com>
    <wisarmy@gmail.com>
<http://google.com>

<wisarmy@gmail.com>

## 反斜杠转义
    \   反斜线
    `   反引号
    *   星号
    _   底线
    {}  花括号
    []  方括号
    ()  括弧
    #   井字号
    +   加号
    -   减号
    .   英文句点
    !   惊叹号
