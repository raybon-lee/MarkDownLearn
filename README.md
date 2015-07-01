# MarkDownLearn
===========

---
**希望和我一样不知道git怎么用的新手来学习一些Markdown语法，让我们的第一印象留给别人，首席我们要从README.md 开始学习了，这个我也是查询了一些资料，还有缺少的在以后用到了继续补充，临时简单的记录学习一下**

---

# 一级标题这样写（H1）
## 二级标题这样写（H2）

...

###### 六级标题的话就这样（H6）

## 具体使用情况请下载demo查看README.md 源文件

---
# 文字格式

**两星代表粗体文字** <br>
*一星代表斜体文字* <br>
~~我被删除了~~ <br>

--- 

# 列表
---

> 无序列表

* 第一个文件
* 第二个文件
* 第三个文件

> 有序列表

1. 我是1
2. 项目2
3. 项目3

   >-  * 项目1
   >-  * 项目2

---

# 其他



> **Note:** You can find more information:

> - about **Sequence diagrams** syntax [here][7],


### Support StackEdit


[^stackedit]: [StackEdit](https://stackedit.io/) is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.
[7]: http://math.stackexchange.com/
---
## 多行文本，可以在首行增加两个Tab

        你好，我前面有两个Tab了
        我前面也有两个
        你好，要下班了，真舒服啦

## 部分文字高亮的使用，就是ESC下面用英文输入
格式：` 文字`
`ME` YOU 

## 添加图片

格式：`![图片名字]（链接地址)`
![image icon](default.png)

## 链接地址
[我的新浪博客](http://blog.sina.com.cn/s/articlelist_3034537011_0_1.html)
## 引用的格式

>- 第一个文件
>- 第二个文件

> - **特殊引用**

## 水平线

***

## 代码

`<hello world>`

#### <i class="icon-pencil"></i> Rename a document

#### 代码块高亮状态

```//FOO
Welcome to China ! <br>
 hello word!
```

### 定义
>TEAM 1 
>-: Definition A
>-: Definition B

    > part of definition B

### Footnotes

You can create footnotes like this[^footnote].
 [^footnote]: Here is the *text* of the **footnote**.


##  表格的使用格式如下
table_name | content
-------|--------
cell1  | value1
cell2  | string2
***
### 多级表格使用
| Item     | Value | Qty   |
| :------- | ----: | :---: |
| Computer | $1600 |  5    |
| Phone    | $12   |  12   |
| Pipe     | $1    |  234  |

***

### 目录用法
*[背景介绍](#背景介绍)
*[项目介绍](#项目介绍)
*[使用说明](#使用说明)
*[其他](#其他)


<a name="背景介绍"></a><br>

<a name="获取代码"></a>

***

### UML diagrams

>You can also render sequence diagrams like this:

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```


>And flow charts like this:

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```





