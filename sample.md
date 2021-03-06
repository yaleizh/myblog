---
title: github markdown格式模板 
tags: ["github", "markdown"]
excerpt: 这是根据github markdown写的一篇模板
date: 2019-04-07
---
---
# 一 引言
---
# 二 正文部分

## 2.1 第一小节

### 2.1.1 第一小小节

#### 2.1.1.1 基本格式

> 引用
>
> 引用


* 红
* 绿
* 蓝

1. 红
2. 绿
3. 蓝

- [ ] a task list item
- [x] completed

**加粗**

~~划线~~

#### 2.1.1.2 插入图片

![image1](http://pic.yupoo.com/yaleizh/fc8c76e8/13ac2851.jpg )

<div align=center>图1<div align=left> 

<div align=center><img src="http://pic.yupoo.com/yaleizh/fc8c76e8/13ac2851.jpg" width = 40% height = 40% /><div align=left> 

<div align=center>图2<div align=left> 

#### 2.1.1.3 插入表格

<div align=center>表1<div align=left> 

| Item      |    Value | Qty  |
| --------: | :--------| :---:|
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |

#### 2.1.1.4 插入代码块

`printf()`

```latex
\{\frac{4}{5}, \sqrt{49},
\, 6, \overline{3}, \, 7\sqrt{5}
\}
```

```python
#-*- coding:utf8-*-
num = 5     
if num == 3:            # 判断num的值
    print 'boss'        
elif num == 2:
    print 'user'
elif num == 1:
    print 'worker'
elif num < 0:           # 值小于零时输出
    print 'error'
else:
    print 'roadman'     # 条件均不成立时输出
```

#### 2.1.1.5 插入公式

<div align=center>
<a href="https://www.codecogs.com/eqnedit.php?latex=a=\frac{b}{c}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a=\frac{b}{c}" title="a=\frac{b}{c}" /></a>
<div align=left> 

#### 2.1.1.6 插入流程图
```Mermaid
  graph LR
    A[Hard edge] -->B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```
## 2.2 字体

---
# 三 结语

我的github链接:[我的github][1]
或者链接：[Baidu](www.baidu.com)
邮箱:<i@GitPress.io>

> **流程图**[语法][2]以及**时序图**[语法][3]

  [1]: https://github.com/yaleizh/myblog/blob/master/samples.md
  [2]: http://adrai.github.io/flowchart.js/
  [3]: http://bramp.github.io/js-sequence-diagrams/

