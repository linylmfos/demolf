# demo2

## 链接 demo

### 内嵌式链接

- 外部链接  [百度](http://www.baidu.com)
- 内部链接1  [README.md](README.md)
- 内部链接2  链接本文档的其他部分： [代码块](mdLearn.md#代码块-demo)

### 引用式链接

外部链接： [百度]  
外部链接： [百度][baidu]  
内部链接: 链接仓库的其他文件: [mdLearn]  
内部链接2，链接本文档的其他部分： [代码块 demo](mdLearn.md#代码块-demo)  

## 图片 demo
图片的markdown语法  
![alt](url text)  
- 外部图片 demo
![baidu](https://www.baidu.com/img/bd_logo1.png?where=super "百度网站")  

- 仓库内的图片 demo  
![](images/yixiu.jpg)  

## 引用 demo

> 这是一个引文  
——出自《论语》

多次引用   
>>> 这是多重引文


<!--- 下面是本文档中用到的链接 -->
[百度]: http://www.baidu.com

[百度]: http://www.baidu.com
[mdLearn]: mdLearn.md

## 水平分割线 

hello     

---
水平分割线  
<hr> 

<img src="https://www.baidu.com/img/bd_logo1.png?where=super" >

图片居中

<p align="center">
    <img src="https://www.baidu.com/img/bd_logo1.png?where=super" >
</p>  

## GFM demo  
- [x] task 1
- []  task 2
- [x] task 3
## 水平居中  
<p align="center">hello</p>  

## 表情符号  
:smile  
## 代码块 demo  

- 行内代码   
这个代码中用来声明变量是 var a = 10, 打印变量内容是`console.log` 函数的调用   

```javascript
  const a = 10;
  for(var i=0;i<5;i++>) {
      console.log(i);
  }
```

