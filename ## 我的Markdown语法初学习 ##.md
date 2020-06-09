## 我的Markdown语法初学习 ##

# 这是一级标题 #
## 这是二级标题 ##
### 这是三级标题 ###

**这是加粗的文字**

*这是倾斜的文字*

***这是倾斜加粗的文字***    

~~这是加删除线的文字~~

>这是引用的内容
>>这是二级引用的内容

----------------------------------

![hero](https://www.legends-killer.cq.cn/louie_senpai_siren/images/temp.jpg "并不知道是哪个角色")

-------------

[百度](http://baidu.com)

<a href="https://xststone.github.io/blog.github.io/" target="_blank">Stone's Blog</a>

- 列表内容
+ 列表内容
* 列表内容

1. 列表内容
2. 列表内容
3. 列表内容

- 一级无序列表内容_1
   1. 二级有序列表内容_1
   2. 二级有序列表内容_2
   3. 二级有序列表内容_3
- 一级无序列表内容_2

tableTitle|tableTitle|tableTitle
---|:--:|---:
content|content|content
content|content|content

- 第二行分割表头和表格内容
    - "-"有一个就可以，多加几个是为了对齐
- 文字默认居左
   - "-"两边加":"表示文字居中
   - "-"右边加":"表示文字居右

--------------------

`printf("This is a single line of code");`

```
    void doWork() {
        printf("This is");
        printf("multi-line code"); 
    }
```


```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
好像这个flow并不能运行
I don't know why
```

<a href="javascript:scroll(0,0)">-- 返回顶部 --</a>