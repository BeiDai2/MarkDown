# demo4

## 混合强调样式

基本强调样式:

- **加粗**
- *倾斜*
- ~~删除~~

混合强调样式：

- ***加粗倾斜***
- **~~加粗删除~~**
- *~~倾斜删除~~*
- ***~~加粗倾斜删除~~***

## 图片链接

基本文字链接：

[链接文字](URL)

[百度](http://www.baidu.com)

基本图片：

![alt](URL txt)

![](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white.png)

图片链接：

[![](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white.png)](http://www.baidu.com)

[![][baidu_logo]][baidu]


## 引用链接的问题

基本引用链接的用法：

good:
[百度][baidu]
[百度网站][baidu]

low:
[百度]  
[百度网站]



<!--  以下是文本中的链接 -->

[baidu]: http://www.baidu.com
[baidu_logo]:https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white.png
[百度]: http://www.baidu.com
[百度网站]: http://www.baidu.com


## 多级列表
- 问题1：如何打断：空行不行，需要文字段落
1. item1
  1. item1.1
  1. item1.2
2. item2

文字打断

3. item3
4. item4

- 问题2：打断的列表，如何续上
1. item1
  1. item1.1
  1. item1.2
2. item2

    文字续上
	
3. item3
4. item4
