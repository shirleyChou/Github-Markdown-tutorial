该文档用来记录和测试GitHub上的各种Markdown语法。
***
###                    Author:Shirley



## <a name="index"/>目录
* [标题](#title)
* [横线](#line)
* [文本](#text)


<a name="title"/>
大标题（等号与文字紧邻） == 一级标题
=
中标题（减号与文字紧邻） == 二级标题
-
#一级标题  
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题


##<a name="line"/>横线
等号表示实线，一个就可以

=
-, *, _ 表示虚线，写三个以上

---
***
___

##<a name="text"/>显示文本
### 普通文本
等号/减号与文字间空一行，则显示普通文本/直接输入的文本就是普通文本

=
### 换行符
用\<br>表示换行符<br>
也可以使用\<br/>

### 
多行文字  
每行行尾
加两个Tab

## 文本高亮
`Thanks!` Please `call` me!

## 给超链接显示文字
[GitHub上README.md教程](http://blog.csdn.net/kaitiren/article/details/38513715 "悬停显示")
[GitHub test](https://github.com/guodongxiaren/README) 

# 插入符号
## 圆点
* 这是一个圆点符
* 这也是一个圆点符

* 一级结构
  * 一个Tab二级结构
    * 两个Tab三级结构

## 缩进
>Markdown 是一种轻量级的标记语言，由John Gruber和AaronSwartz创建，最初是用来定义一种将文本转换成html文件的工具markdown，项目主页见：Markdown。它是开源项目，并以BSD-style许可证的许可方式以插件形式或内容管理系统形式发布。 本文就是用Markdown书写的，可能在blog里面不是很好看。将其复制到我推荐的Markdown工具里面，就可以看到效果了。
>数据结构  
>>>二叉树  
>>>>>满二叉树

# 插入图片
## 来源于网络的图片
![](http://www.baidu.com/img/bdlogo.gif)  
![baidu](http://www.baidu.com/img/bdlogo.gif) 
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo") 
[baidu](http://www.baidu.com/img/bdlogo.gif)

## 给图片加入超链接
[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo" 

## 插入代码片段
```Python
[str(char) for char in int] //Python
```
```Java
public static void main(String[]args){} //Java
```
