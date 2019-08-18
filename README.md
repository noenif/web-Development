# web-Development
###### < 小于 &lt; &#60;
###### > 大于 &gt; &#62;
###### & &符号 &amp; &#38;
###### " 双引号 &quot; &#34;
###### 其他常用的字符实体(Character Entities)
###### 显示结果 说明 Entity Name Entity Number
###### ? 版权 &copy; &#169;
###### ? 注册商标 &reg; &#174;
###### × 乘号 &times; &#215;
###### ÷ 除号 &divide; &#247;

类setext语法

这是类setext语法
===============
这是次级setext短路
-----------------
atx语法

# 这是atx第一层
## 这是atx耳机语法
## 让我看看这个有什么不一样,貌似一样的 ####
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.
> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
>
>      return shell_exec("echo $input | $markdown_script");

>      > + four tab key ,The advantage of using this is that you can't translate code.
*   Red
*   Green
*   Blue
+   Red
+   Green
+   Blue
<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>
 <div class="footer">
        &copy; 2004 Foo Corporation
    </div>
    
* * *

***

*****

- - -

---------------------------------------
This is [an example](http://example.com/ "Title") inline link.
[This link](http://example.net/) has no title attribute.

I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or
[MSN](http://search.msn.com/ "MSN Search").

这是[谷歌][google]

  [google]: http://google.com/        "Google"
  #### 你会发现不一样
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
  
  
  *single asterisks*

_single underscores_

**double asterisks**

__double underscores__
# 很多什么一个空格或者回车机会触发神奇的潘多拉魔盒
un*frigging*believable
Use the `printf()` function.
``There is a literal backtick (`) here.``
A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``
Please don't use any `<blink>` tags.
<p><code>&amp;#8212;</code> is the decimal-encoded
equivalent of <code>&amp;mdash;</code>.</p>

![Alt text](http://pic31.nipic.com/20130801/11604791_100539834000_2.jpg)

![Alt text][id]

[id]: http://pic31.nipic.com/20130801/11604791_100539834000_2.jpg  "Optional title attribute"

<address@example.com>

\*literal asterisks\*

# 到此为止,我们的markdown教程全部结束
