# 函数
### 返回值，就是函数执行的结果
+ 使用return 来设置函数的返回值。
+ 语法：return 值;该值就会成为函数的返回值，可以通过一个变量来接收返回值
+ return后边的代码都不会执行，一旦执行到return语句时，函数将会立刻退出。
+ return后可以跟任意类型的值，可以是基本数据类型，也可以是一个对象
+ 如果return后不跟值，或者是不写return则函数默认返回undefined。
+ break、continue和return
```
break 退出循环
continue 跳过当次循环
return 退出函数
```
### 参数，函数的实参也可以是任意的数据类型
### 方法（method）
+ 可以将一个函数设置为一个对象的属性,当一个对象的属性是一个函数时，我们称这个函数是该对象的方法
+ 对象.方法名();
+ 函数名();