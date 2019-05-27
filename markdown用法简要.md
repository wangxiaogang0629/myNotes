## markdown 编辑
---
##### Markdown 的语法全由一些符号所组成，这些符号经过精挑细选，其作用一目了然。

#### 标题
	1.类 Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题）
	2.在开头加上#，1-6个代表标题一到标题六
#### 列表
	1.无序列表 +，-，*
	2.有序列表 数字+英文句点，
#### 分隔线 
	1.* * *
	2.***
	3.*****
	4.- - -
	5.---
#### 链接：Markdown 支持两种形式的链接语法： 行内式和参考式两种形式。
	1.行内式：要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可。
This is [an example](http://example.com/ "Title") inline link.

	2.参考式：链接文字的括号后面再接上另一个方括号，而在第二个方括号里面要填入用以辨识链接的标记。
This is [an example][id] reference-style link.

**注意** ：你也可以选择性地在两个方括号中间加上一个空格，接着，在文件的任意处，你可以把这个标记的链接内容定义出来。

This is [an example baidu] [id] reference-style link.
[id]: http://www.baidu.com "baidu"

**链接内容定义的形式为**：

方括号（前面可以选择性地加上至多三个空格来缩进），里面输入链接文字
接着一个冒号
接着一个以上的空格或制表符
接着链接的网址
选择性地接着 title 内容，可以用单引号、双引号或是括弧包着

#### 强调
	1.使用星号（*）和底线（_）作为标记强调字词的符号
	2.被 * 或 _  包围的字词会被转成用 <em> 标签包围
	3.用两个 * 或 _ 包起来的话，则会被转成 <strong>

#### 反斜杠
	\   反斜线
	`   反引号
	*   星号
	_   底线
	{}  花括号
	[]  方括号
	()  括弧
	#   井字号
	+   加号
	-   减号
	.   英文句点
	!   惊叹号
	
#### 表格

> * 可以直接用html或使用 `|` 分割

> * 第二行分割表头和内容。

> * | 竖线居两边：`文字居中`、居右：`文字居右`、居左：`文字居左`

	| thead | thead | thead |
	| ---   | :--:  | ---:  |
	| tbody | tbody | tbody |

| thead | thead | thead |
| ---   | :--:  | ---:  |
| tbody | tbody | tbody |

	 <table>
	    <tr>
    		<th> thead </th>
	    	<th> thead </th>
	    	<th> thead </th>
	    </tr>
	    <tr>
			<td> tbody</td>
			<td> tbody </td>
			<td> tbody </td>
	    </tr>
	</table>
<table>
    <tr>
        <th> thead </th>
        <th> thead </th>
        <th> thead </th>
    </tr>
    <tr>
        <td> tbody </td>
        <td> tbody </td>
        <td> tbody </td>
    </tr>
</table>


#### 代码

>单行首尾单个反引号、多行三个反引号

``` javascript
	function add(a, b) {
	   return a + b;
	}
```

