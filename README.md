该文档用来记录和测试GitHub上的各种Markdown语法。
***
###                    Author:Shirley



## <a name="index"/>目录
* [标题](#title)
* [横线](#line)
* [文本](#text)
    * 普通文本
    * 关于换行
    * 单行文本
    * 多行文本
    * 文本高亮
    * 删除线
    * 斜体
    * 粗体
* [缩进](#Tab)
* [列表](#List)
   * 圆点列表
   * 圆点的层次结构列表
   * 数字列表
   * 复选框列表
* [链接](#link)
    * 让超链接显示文字
    * 锚点
* [图片](#pict)
   * 来源于网络的图片
   * 给图片加入超链接
* [代码高亮](#code)
* [表格](#table)
* [表情](#emotion)


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
<br>

##<a name="line"/>横线
等号表示实线，一个就可以<br>

=
-, *, _ 表示虚线，写三个以上

---
***
___
<br>
<br>

##<a name="text"/>文本
### 普通文本
等号/减号与文字间空一行，则显示普通文本/直接输入的文本就是普通文本

=
### 关于换行
用\<br>表示换行符<br>
也可以使用\<br/>

或者直接在两行文本加一个空行，

也能实线换行效果，不过行间距有点大。

还可以在行尾加上两个空格  
就可以实现换行  

### 单行文本
    这就是单行文本
    
### 多行文本
    多行文字        
    前面空四格      
    行尾加两个Tab       
    就是这样        

### 文本高亮
`Thanks!` Please `call` me!

### 删除线
~~这就是删除线~~

### 斜体
*斜体1*<br>
_斜体2_

### 粗体
**粗体1**<br>
__粗体2__
<br>
<br>

##<a name="Tab"/>缩进
>Markdown 是一种轻量级的标记语言，由John Gruber和AaronSwartz创建，最初是用来定义一种将文本转换成html文件的工具markdown，项目主页见：Markdown。它是开源项目，并以BSD-style许可证的许可方式以插件形式或内容管理系统形式发布。 本文就是用Markdown书写的，可能在blog里面不是很好看。将其复制到我推荐的Markdown工具里面，就可以看到效果了。
>数据结构  
>>>二叉树  
>>>>>满二叉树
<br>
<br>

##<a name="sym"/>列表
### 圆点列表
* 这是一个圆点符
* 这也是一个圆点符

### 圆点的层次结构列表
数字列表也是一样，`*`改成`1.`
* 一级结构
  * 一个Tab二级结构
    * 两个Tab三级结构

### 数字列表
#### 一般效果  
面向对象的三个基本特征：  
1. 封装  
2. 继承  
3. 多态  

#### 自动排序
>在第一行指定`1.`，剩下用`*`或者继续用`1.`表示:

面向对象的七大原则：  
1. 开闭原则
* 里氏转换原则
* 依赖倒转原则
* 接口隔离原则
* 组合/聚合复用原则
* “迪米特”法则
* 单一直则原则

### 复选框列表
- [x] C
- [x] C++
- [x] Java
- [x] Qt
- [x] Android
- [ ] C#
- [ ] .NET
<br>
<br>

##<a name="link"/>链接
### 让超链接显示文字
[GitHub上README.md教程](http://blog.csdn.net/guodongxiaren/article/details/23690801 "Markdown教程")  
[GitHub test](https://github.com/guodongxiaren/README) 

###锚点
[回到目录](#index)  
[回到标题](#title)
<br>
<br>

##<a name=""/>图片
### 来源于网络的图片
![](http://www.baidu.com/img/bdlogo.gif)  
![baidu](http://www.baidu.com/img/bdlogo.gif) 
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo") 
[baidu](http://www.baidu.com/img/bdlogo.gif)

### 给图片加入超链接
[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo" 
<br>
<br>

##<a name="code"/>代码高亮
```Python
[str(char) for char in int] //Python
```
```Java
public static void main(String[]args){} //Java
```
<br>
<br>

##<a name="table"/>表格
表头1  | 表头2
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| 表头1  | 表头2|
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| 名字 | 描述          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

表格中也可以使用普通文本的删除线，斜体等效果

| 名字 | 描述          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

表格可以指定对齐方式

| 左对齐 | 居中  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
<br>
<br>

##<a name="emotion"/>表情
根据http://www.emoji-cheat-sheet.com/  
提供的符号码可以输出不同的emoji表情，比如说：  
`:wink:`:wink:  
`smile` :snile:  
