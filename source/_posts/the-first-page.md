---
title: the first page
date: 2019-10-24 23:15:04
tags:
---


# 参考文档
http://note.youdao.com/iyoudao/?p=2411&vendor=unsilent14

# 一级标题
## 二级标题（多一个#标题号降低一级）

### 无序列表
- 列表1
- 列表2
- 列表3


### 有序列表
1. 列表1
2. 列表2
3. 列表3

<!-- more -->

###### 引用
> 记录，成为更好的自己。--有道云笔记


*这是斜体*
**这是粗体**

#### 注意：符号与文本之间无须空格


#### 插入链接
[链接如下]（http://note.youdao.com/iyoudao/?p=2411&vendor=unsilent14）

#### 插入图片

![本地图片](../images/a.jpg)

---

![外部图片链接](https://uploadfile.huiyi8.com/2014/1020/20141020045816290.jpg)

### 分割线
这是第一段内容
***
这是第二段内容


### 表格
header 1 | header 2
---|---
row 1 col 1 | row 1 col2
row 2 col 2 | row 2 col2

### 表格2
| Item     |    Value | Qty  |
| :--------| --------:| :-- :|???


### To-do List
- [x] 已完成项目1
- [ ] 待办事项


### 流程图
###### 自上而下的顺序

```
graph TB
A-->B
```
###### 自下而上的顺序
```
graph BT
A-->B
```
#### 稍复杂流程图
```
graph TD
    A[Chriatmas] -->B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[Car]
```

### 甘特图
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求: 2016-03-01, 10d
section 中期阶段
跟进开发: 2016-03-11, 15d
section 后期阶段
走查测试: 2016-03-20, 9d
```
