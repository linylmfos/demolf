### 多层嵌套  
> aaaaaaaaa
>> bbbbbbbbb
>>> cccccccccc  

### 引用  
> hello world!  
##### 多行式  
> hello world!  
hello world!  
hello world!  

### 行内标记  
标记之外`hello world`标记之外  

### 代码块  
```
<div>   
    <div>内容</div>
    <div>内容</div>
    <div>内容</div>
</div>
```

```javascript
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
``` 
## 脚注
Markdown[^1]  
[^1]: Markdown是一种纯文本标记语言   

## 自动邮箱链接  
<xxx@outlook.com>  

### 插入链接
代码1(内链式)
注：{:target="_blank"}跳转方式兼容性一般 ，多数第三方平台不支持跳转

[百度1](http://www.baidu.com/" 百度一下"){:target="_blank"}   

代码2(引用式)

[百度2][2]{:target="_blank"}
[2]: http://www.baidu.com/   "百度二下"

<iframe height=498 width=510 src='http://player.youku.com/embed/XMjgzNzM0NTYxNg==' frameborder=0 'allowfullscreen'></iframe>  

[![](./youku2.png)](http://v.youku.com/v_show/id_XMjgzNzM0NTYxNg==.html?spm=a2htv.20009910.contentHolderUnit2.A&from=y1.3-tv-grid-1007-9910.86804.1-2#paction){:target="_blank"}   

