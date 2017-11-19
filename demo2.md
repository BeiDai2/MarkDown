# demo2

## 链接 demao

### 内嵌式链接
- 外部链接：(百度)(http://www.baidu.com)
- 外部链接: [百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文件：[demol](demo1.md)
- 内部链接2，链接本文档其他：[代码块 demo](demo2.md#代码块-demo)

### 引用式链接
- 外部链接：[百度]
- 外部链接: [百度][baidu]
- 内部链接1，链接仓库的其他文件：[demo1]
- 内部链接2，链接本文档其他：[代码块 demo]

## 图片 demo  
### 图片的内嵌式链接
<!--- [alt](url text) -->
- 外部图片
![baidu](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white.png "百度网站")
- 内部图片
![arduino](images/arduino.png)

###图片的引用式链接：
- 外部图片
![baidu][baidu_logo]
- 内部图片
![][arduino_png]

## 引用 demo

> 这是一个引文。  

出自《出处》

多次引用。
>>> 这是多重引文.


## 代码块 demo

- 行内代码

这个代码中用来声名变量 `var a = 10`,打印变量内容是`console.log` 函数的调用.


- 快式代码

```javascript
car a = 10;
console.log(a);
```


    car a = 10;
    console.log(a);


<!--- 下面是本文档中用到的链接  -->

[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]: demo1.md
[代码块 demo]: demo2.md#代码块-demo

[arduino_png]: images/arduino.png
[baidu_logo]: https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white.png
