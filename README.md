# markdown
## 语法1

+ 标题
+ 段落  
段落和段落之间，段落和标题之间加空行。  
行最后加2个空格换行，下一行缩进  
    缩进
    缩进  
视图->自动换行

+ 强调  
*斜体*  
**粗体**  
***斜体加粗***    
*可以用_代替  
~~删除线~~  
工具->插件安装->GFM Viewer

+ 列表
* 无序列表，*加空格
  * *可用-代替
  1. 嵌套加2个空格，数字加空格

## 语法2
+ 链接
### 内嵌式链接
1. 外部链接：[百度](http://www.baidu.com)
2. 内部链接1，链接仓库的其他文件：[test](test.md)
3. 内部链接2，链接本文档的其他部分：[链接](markdown.md#链接)
### 引用式链接
1. 外部链接：[百度]
4. 外部链接：[百度][baidu]
2. 内部链接1，链接仓库的其他文件：[test]
3. 内部链接2，链接本文档的其他部分：[链接]


+ 图片  
外部图片  
![baidu](https://www.baidu.com/img/dong_66cae51456b9983a890610875e89183c.gif "百度网站")  
内部图片
![](image.gif)  
引用  
外部图片  
![baidu][baidu_image]
内部图片
![][image]


+ 引用
>这是一个引文  

多重引用
>>另一个引文

+ 代码块
行内代码    
`行内代码`  
代码块
```python
echo php
```

## 语法3
+ 表格

|表头|这是|
|:---|---:|
|表格|表格11111111|

+ 水平分隔线
---
***
___
+ HTML语法
<p align='center'>hello</p>
+ GFM语法  
task  

- [x] 任务

:snake:
<!--下面是本文档中用到的链接-->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[test]:test.md
[链接]:markdown.md#链接
[学习]:markdown.md#学习
[baidu_image]:https://www.baidu.com/img/dong_66cae51456b9983a890610875e89183c.gif
[image]:image.gif
