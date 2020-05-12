# Python

#### 查询数据类型

* type()
* isinstance
* 的区别在于
	* type()不会认为子类是一种父类类型。
	* isinstance()会认为子类是一种父类类型。

```
a = 1;
print(type(a)); // <class 'int'>
print(isinstance(a, int)); // True
```

#### String 字符串

* 截取 [start:end]
* 取消反斜杠转义 在字符串前添加r `r'hello\nworld'`

#### List 列表

* 截取 [start:end]
* 截取 [start:end:step] step：步长，间隔位置