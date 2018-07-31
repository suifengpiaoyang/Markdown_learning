# Markdown_learning

* ## 目录

    * [学习文档](#学习文档)  
    * [换行与链接](#换行与链接)  
    * [图片](#图片)  
    * [强调](#强调)  
    * [标题](#标题)  
    * [引用](#引用)  
    * [代码块](#代码块)  
    * [表格](#表格)  
    * [列表](#列表)  
    * [跳转](#跳转)  
    * [缩进](#缩进) 
    * [疑问](#目前无法解决的疑问)  

---------------------------------

### 学习文档

[Markdown维基百科](https://zh.wikipedia.org/wiki/Markdown#%E5%9B%BE%E7%89%87)  
[Markdown学习文档（中文）](https://markdown.tw/)  
[Markdown学习文档（英文）](https://www.markdownguide.org/basic-syntax/)  
[Markdown表格](http://xianbai.me/learn-md/article/extension/table.html)  
[Maekdown页面内跳转学习教程](https://www.jianshu.com/p/4898c2e9a36d)  

[回到顶端](#markdown_learning) 

---------------------------------

### 换行与链接

换行：末尾输入两个空格可强制换行。输入\<br>也是可以换行的，就是没有输入空格方便。  

链接：
[Aaron Swartz](https://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)

[回到顶端](#markdown_learning) 

-------------------------

### 图片

图片显示有两种方式：  
第一种方式：\![alt]\(url)  
    alt为图片显示失败时显示的的文字，url为图片的网址。这种方式最简单便捷，但是无法控制图片的大小和位置。  
第二种方式：  
    就是按照HTML的标准来放置图片。自然参数众多，可以控制图片的各种位置和大小。就如同下面所展示的。

图片显示：  
<img src='https://github.com/suifengpiaoyang/Markdown_learning/blob/master/360px-Aaron_Swartz_profile.jpg' with = 100 height = 200 alt = '头像'>

[回到顶端](#markdown_learning) 

-------------------------

### 强调  
*强调1*  
**强调2**  
***强调3***  

[回到顶端](#markdown_learning) 

----------------------

### 标题

# 一级标题
## 二级标题   
### 三级标题  
#### 四级标题   
##### 五级标题  
###### 六级标题   

[回到顶端](#markdown_learning) 

-----------------------

### 引用

>Markdown是一种轻量级标记语言，创始人为约翰·格鲁伯（英语：John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档”。[4]这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。<br>John Gruber 在 2004 年创造了 Markdown 语言，在语法上有很大一部分是跟[亚伦·斯沃茨（Aaron Swartz）](https://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)共同合作的。这个语言的目的是希望大家使用“易于阅读、易于撰写的纯文字格式，并选择性的转换成有效的XHTML（或是HTML）”。 其中最重要的设计是可读性，也就是说这个语言应该要能直接在字面上的被阅读，而不用被一些格式化指令标记（像是RTF与HTML）。 因此，它是现行电子邮件标记格式的惯例，虽然它也借鉴了很多早期的标记语言，如：Setext、Texile、reStructuredText。 许多网站都使用 Markdown 或是其变种让用户更利于讨论。例如：GitHub、reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge等。  

嵌套引用：
>这是第一层
>>第二层
>>>第三层

[回到顶端](#markdown_learning) 

--------------------------

### 代码块

```python
print('Markdown')
```

[回到顶端](#markdown_learning) 

----------------------
### 表格

表格的创建有一个很重要的隐性规则，就是在<strong>表格数据的上一行不能有文字！如果有文字，则不识别为表格！</strong>虚线上面一行是表头，表头的文字格式加粗：

|x|y|z
|---|---|---
|3|4|5

* 表格对其方式：  

    :--- 代表左对齐  
    :--: 代表居中对齐  
    ---: 代表右对齐  

[回到顶端](#markdown_learning) 

-----------------------
 ### 列表
 
无序列表：
* a
* b 
* c

多层列表：
* 1
    * 1-1
        * 1-1-1

[回到顶端](#markdown_learning) 

-----------------------

### 跳转

[跳转到标题](#markdown_learning)  
[跳转到一级标题](#一级标题)  
[跳转到二级标题](#二级标题)  

>**注意**：
>
>* [锚点][锚点的定义]的目标内容中**不能有大家字母和空格**，所以如果锚点目标的目标内容中有大写字母或空格，则需要在定义锚点中的目标内容时，**把大写字母改成小写字母，把空格改成 -；**
>* [锚点][锚点的定义]的目标内容中不能含有以下字符：
半角点(即英文中的句号).
>
>作者：科研者
>链接：https://www.jianshu.com/p/4898c2e9a36d
>來源：简书
>简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。

[回到顶端](#markdown_learning) 

-----------------------
### 缩进
markdown实现缩进的方法

|类型|实现方式|
|:--:|:--:|
|半角空格|\&ensp; 或 \&#8194;|
|全角空格|\&emsp; 或 \&#8195;|
|不换行空格|\&nbsp; 或 \&#160;|

[回到顶端](#markdown_learning) 

------------------------

### 目前无法解决的疑问

1.在上面表格一项的说明文字中，我本想用markdown强调语法强调某些内容（\*\*），但是失效了。只得使用html的强调语法。目前不知道原因。

2.文件树

https://stackoverflow.com/questions/19699059/representing-directory-file-structure-in-markdown-syntax

https://meta.stackexchange.com/questions/147467/is-there-a-good-way-to-represent-file-structure-in-a-question-answer

https://stackoverflow.com/questions/23989232/is-there-a-way-to-represent-a-directory-tree-in-a-github-readme-md

[回到顶端](#markdown_learning) 

------------------------
