---

---



## 目录

输入[toc]

[toc]

## 标题 
几个#代表几级标题  从一级到六级，和<h1> 到<h6> 一样

##  块引用

> 引用
>  引用

## 清单 无序列表和有序列表
无序列表的符号有 *  +   -   

下级在上级基础上前面多加两个空格，符号与内容直接有一个空格。

* 无序列表
	*  wxlb
+ 无序列表
- 无序列表

有序列表

1.有序列表
2.有序列表

## 任务列表
带有标记为[] 或者[x]的列表

- [ ] 未完成列表
- [x] 已完成列表

## （有栅栏）代码块
输入三个反引号``` ,在三个反引号之后可添加语言标识符，将通过语法高亮显示代码块

``` php
function helloWorld(){
echo 'helloWorld';
}
```

    hhhh
    hahahah
    hahah

## 数学块
添加数学表达式 输入$$

## 桌子 表
输入| First Header | Second Header |
通过: 在标题行中包含冒号，可以定义左对齐，右对齐，居中对齐
使用`:---------:`居中 ，使用`:----------`居左 ， 使用`----------:`居右。

| First Header | Second Header |
|-----------------|----------------------|
|Content Cell | Content Cell        |
|Content Cell | Content Cell        |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

## 脚注
脚注[^jaiozhu]      \[^jiaozhu]:内容

您可以像这样创建脚注[^1]

[^1]: 这是脚注的内容

## 水平尺  水平线
在空白行上输入***(颜色浅)或者---   ,---在文章顶部输入，会引入一个元素块

***
---

##网址
URL作为链接，并用[方括号括起来]

[百度](www.baidu.com)

##图片
图像的语法与链接相似，但是在方括号开始之前需要加!感叹号

![avatar](/home/zhou/2D.png)

![avatar]([http://baidu.com/pic/doge.png](https://links.jianshu.com/go?to=http%3A%2F%2Fbaidu.com%2Fpic%2Fdoge.png))

![avatar][base64str]

[base64str]: data:image/png;base64,iVBORw0......

![基础用法](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9hdmF0YXIuY3Nkbi5uZXQvNy83L0IvMV9yYWxmX2h4MTYzY29tLmpwZw#pic_center =30x30)

## 斜体
使用星号*和下划线_是斜体，  和<em>类似

*单星号*
_单下划线_

## 加粗
使用** 或者__ 会使字体加粗

**双星号**
__双下划线__

斜粗体是***斜粗体***

## 删除线

~~双波浪线~~

## 下划线

<u>HTML下划线标签</u>

## 表情符号

## HTML
可以使用HTML来设置Markdown不支持的内容样式
<span style="color:red">红色文本</span>

<p style="color:blue;size:50px">
    蓝色大字
</p>

## 嵌入内容
<iframe height='265' scrolling='no' title='Fancy Animated SVG Menu' src='http://codepen.io/jeangontijo/embed/OxVywj/?height=265&theme-id=0&default-tab=css,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'></iframe>
