# Demo 02
## 链接
### 内嵌式链接
- 外部链接 [百度](https://www.baidu.com)
- 内部链接：仓库文件 [demo1](demo1.md)
- 内部链接：本页面链接  [代码块](demo2.md#代码块)
### 引用式链接
- 外部链接 [百度]
- 外部链接 [百度][baidu]
- 内部链接：仓库文件 [demo1]
## 图片
![百度](https://www.baidu.com/img/fnj_96d95207b4a706738f1b8be3b41ea9f3.gif)
## 引用
> 这是一段引文。 
 
				--出自《出处》

多次引用。  
>>> 这是多次引文


## 代码块
<!-- 行内代码 -->
这个代码中声明的变量是`var c = 0`, 执行方法`sum()`函数调用
<!-- 块代码 -->
```javascript
	var c = 0;
	function sum(){
		c += 1;
	}	
```
```java
	class Person{
		private String name;
		private int age;
	}
```

```python
	def show_table():
		s = "table"
		print "Table is : %s" %s
```

<!-- 所有的链接放在最后定义 -->
[百度]:https://www.baidu.com
[baidu]:https://www.baidu.com
[demo1]:demo1.md
