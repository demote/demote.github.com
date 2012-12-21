---
layout: post
title: "markdown 语法"
description: ""
category: program, markdown
tags: []
---
{% include JB/setup %}

---
说明:

Markdown是一种轻量的标记语言,目的为“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档(to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML))”. 更详细的说明参考 

[Wikipedia:Markdown](http://en.wikipedia.org/wiki/Markdown).   

本文仅总结(我)常用的语法以作为备忘, 更完整的Markdown语法文档请参考:

- [Markdown Syntax](http://daringfireball.net/projects/markdown/syntax)
- [Markdown 语法说明(繁体)](http://markdown.tw/)
- [Markdown 语法说明(简体)](http://wowubuntu.com/markdown/)

---

##标题

可以通过在标题前添加"#"来标示该行文字为标题文字. 如:

    #   这是标题一  #
    ##  这是标题二  ##
    ### 这是标题三  ###
    ######  这是标题六  ######

即可以通过"#"的个数标示不同等级的标题, "#"到"######"表示标题一至标题六. 其中只有行首的"#"可以标记标题文字,行尾的"#"仅为美观,并不会起到任何作用,即:

    #   这是标题一
    #   这也是标题一    #

上述两种方式无任何不同.

##换行

在Markdown源码中默认是不换行的,如果想要换行,有两种方式可以实现:

<li> 在换行前在行尾添加2个以上的空格 </li>
<li> 在两行中间添加空行 </li>

以上两种方式均可实现显示换行,即:

    这是一行文字.

    这是第二行文字.
或

    这是一行文字.<空格><空格>
    这是第二行文字.

可以实现换行的效果.

##列表

**有序列表**

可以通过在每个列表项前添加"-"或"+"以标示. 即:

    - Item 1
    - Item 2
    - Item 3

**有序列表**

有序列表可以通过在列表项前添加数字+"."表标示. 即:

    1. Item 1
    2. Item 2
    3. Item 3

##代码区块
在文本中插入代码区块可以通过在代码段的每行前添加4个空格或一个制表符的方式标示. 如:
    This is normal text.
        //code begin
        int main(void)
        {
            printf("hello world!\n");
            return 0;
        }
        //code end

如果需要语法高亮等其他特性,可以使用[Github:Gist](https://gist.github.com/)或其他插件方式.   
如果需要在行内插入小段代码,可以使用反引号(`` ` ``)进行标记,如:

    Here is a sample code for `printf()` function.  

产生的效果为:       

Here is a sample code for `printf()` function.

##分割线
如果需要插入分割线,可以在一行中插入3个以上的"-"或者"\*"来标示. 如:

    ---

    -------

    ***

    * * *

均可在当前行插入分割线.

##超链接
插入超链接可以通过中括号(`[ ]`)+圆括号(`( )`)的方式表示.如:

    [this is a link to somewhere](http://www.somewhere.com)

如果超链接的提示文字与链接相同,可以使用一种更简单的方式标示,即使用尖括号(`<` `>`)将超链接包含起来即可. 如:

    <http://www.somewhere.com>


##图片
Markdown 使用一种和链接很相似的语法来标记图片,方法如下:

        ![Alt text](/path/to/img.jpg)

目前并没有方法可以指定图片的大小,如果有需要,则需要使用HTML中的`<img>`标签进行. 如:

        <img class='inset right' src='/images/test.jpg' title='test img' alt='this is a test img' width='120px' />

---eof---
