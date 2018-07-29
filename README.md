# Markdown_learning
Markdown学习

[Markdown维基百科](https://zh.wikipedia.org/wiki/Markdown#%E5%9B%BE%E7%89%87)  
[Markdown学习文档](https://markdown.tw/)  

-----------------------------------

换行：末尾输入两个空格可强制换行。输入\<br>也是可以换行的，就是没有输入空格方便。  

链接：
[Aaron Swartz](https://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)

图片显示有两种方式：  
第一种方式：\![alt]\(url)  
    alt为图片显示失败时显示的的文字，url为图片的网址。这种方式最简单便捷，但是无法控制图片的大小和位置。  
第二种方式：  
    就是按照HTML的标准来放置图片。自然参数众多，可以控制图片的各种位置和大小。就如同下面所展示的。

图片显示：  
<img src='https://github.com/suifengpiaoyang/Markdown_learning/blob/master/360px-Aaron_Swartz_profile.jpg' with = 100 height = 200 alt = '头像'>

强调：  
*强调1*  
**强调2**  
***强调3***  

标题：  
# 一级标题
## 二级标题   
### 三级标题  
#### 四级标题   
##### 五级标题  
###### 六级标题   

引用：
>Markdown是一种轻量级标记语言，创始人为约翰·格鲁伯（英语：John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档”。[4]这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。<br>John Gruber 在 2004 年创造了 Markdown 语言，在语法上有很大一部分是跟[亚伦·斯沃茨（Aaron Swartz）](https://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)共同合作的。这个语言的目的是希望大家使用“易于阅读、易于撰写的纯文字格式，并选择性的转换成有效的XHTML（或是HTML）”。 其中最重要的设计是可读性，也就是说这个语言应该要能直接在字面上的被阅读，而不用被一些格式化指令标记（像是RTF与HTML）。 因此，它是现行电子邮件标记格式的惯例，虽然它也借鉴了很多早期的标记语言，如：Setext、Texile、reStructuredText。 许多网站都使用 Markdown 或是其变种让用户更利于讨论。例如：GitHub、reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge等。  

嵌套引用：
>这是第一层
>>第二层
>>>第三层

代码块：
```python
print('Markdown')
```

表格：
|x|y|z  
|---|---|---
|3|4|5

无序列表：
* a
* b 
* c

多层列表：
* 1
    * 1-1
        * 1-1-1

:bowtie:

|语法|效果|
|----|-----|
|`*斜体1*`|*斜体1*|
|`_斜体2_`| _斜体2_|
|`**粗体1**`|**粗体1**|
|`__粗体2__`|__粗体2__|
|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|
|`***斜粗体1***`|***斜粗体1***|
|`___斜粗体2___`|___斜粗体2___|
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
|`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~|
