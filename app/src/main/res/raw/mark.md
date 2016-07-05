### 1.标题

行首加井号表示不同级别的标题 (H1-H6),例如：# H1, ## H2, ### H3，#### H4.
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


### 2. 文本
+ 普通文本

 直接输入的文字就是普通文本。需要注意的是要换行的时候不<br>能直接通过回车来换行，需要使用\<br\>.也就是html里面的标签. 注意第三行的`<br>`前加了反斜杠 \\ .目的就是像其他语言那样实现转义，也就是 \<  的转义.

+ 单行文本

        使用两个Tab符实现单行文本.
+ 多行文本

        多行文本和
        单行文本异曲同工，只要在
        每行行首加两个Tab.
+ 文字高亮

如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用 \`  \` 包围起来.`注意`这不是单引号，而是`Tab`上方，`数字1`左边的按键（注意使用`英文`输入法).

### 3. 斜体和粗体

使用 * 和 ** 表示斜体和粗体.

这是 *斜体*,这是 **粗体**.

### 4. 删除线

~~使用\~\~表示删除线.~~

### 5. 外链接

使用 \[描述](链接地址) 为文字增加外链接。

这是去往 [有趣的HTML5和CSS3特效在线演示地址](http://gnipbao.github.io/css3-test/menu.html) 的链接。

### 6.锚点<a name=""/>
我们可以使用HTML的锚点标签（`#`）来设置锚点：[回到目录](#index)
但其实呢，每一个标题都是一个锚点，不需要用标签来指定，比如我们 [回到顶部](#TEST)
不过不幸的是，由于对中文支持的不好，所以中文标题貌似是不能视作标签的。

### 6. 列表

使用 *，+，- 表示无序列表。

- 无序列表项 一
- 无序列表项 二
- 无序列表项 三

二级三级原点

+ 编程语言
    + 脚本语言
        + Python

使用数字和点表示有序列表。

1. 有序列表项 一
2. 有序列表项 二
3. 有序列表项 三

### 7. 数字列表自动排序
也可以在第一行指定`1. `，而接下来的几行用星号`*`（或者继续用数字1. ）就可以了，它会自动显示成2、3、4……
面向对象的七大原则：

1. 开闭原则
* 里氏转换原则
* 依赖倒转原则
1. 接口隔离原则
1. 组合聚合复用原则
1. 迪米特法则
1. 单一直则原则