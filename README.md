# Markdown
## 一、啥是Markdown
Markdown是一种轻量级标记语言，创始人是约翰格鲁伯。它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档。这种语言吸收了很多再电子邮件中已有的纯文本标记的特性。(如果你认真读完了，那么恭喜你，这段来自百度百科，你可以百度一下，再读一遍)。
  
按我的理解，就是使用一些特定的符号，诸如：# = - ...等符号来修饰你的文本内容，使其能够在一些平台上会将其转换成XHTML或HTML的格式，更好地做内容输出。
   
Markdown具体的产生和历史，感兴趣的小伙伴可以自行了解。<br>
这里推荐github上的[younghz/Markdown](https://github.com/younghz/Markdown.git)   

*PS：接下来在文中将使用**MD**来代指Markdown。*

## 二、文本格式篇

### 1.文本标题

#### 1.1 MD写法一：
> 一级标题 使用 =  
> 二级标题 使用 -   
> **使用特点**：需在文本中占据两行，第一行是标题内容，第二行是**至少三个连续相同**的 = 或 - <br>具体格式如下：
>
>一级标题   
>`=======`
>
>二级标题   
>`-------`
    
#### 1.2 实际展示一：
# 一级标题
## 二级标题

#### 1.3 MD写法二：
> 使用 **#** 表示1-6级标题。   
> `#` 一级标题   
> `##` 二级标题   
> `###` 三级标题   
> `####` 四级标题   
> `#####` 五级标题   
> `######` 六级标题   
#### 1.4 实际展示二：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

综上所述，我选择方法二... 毕竟它更好记。

### 2.段落
> 前一行和后一行都是**空行**的文本内容，就是段落。  
> 所以段落就是被**两空行夹击**的。       
>
> (段落前空行，这行不能有东西，谢谢配合)
>  
> 我是段落内容，巴拉巴拉巴拉...
>   
> (段落后空行，这行不能有东西，谢谢配合)

#### 段落效果：

我是段落内容，巴拉巴拉巴拉...