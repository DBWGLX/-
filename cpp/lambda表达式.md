lambda是一种匿名函数，可以调用上文，传入参数，然后像函数一样执行，最后返回结果。
可以用function<()>包装器来命名。
可以在任何地方写，更简洁，方便。


=========
1.可以编写内嵌的匿名函数

2.定义一个lambda表达式后，编译器会自动生成一个匿名类（这个类当然重载了()运算符），我们称为闭包类型（closure type）。
像sort的参数是类。当比较逻辑较为简单时，定义一个类显得冗余。
极大简化了代码。

3.[ ] lambda捕捉块,定义捕捉模式以及变量
[capture] （parameters） mutable ->return-type {statement};  箭头指向返回值！
可以忽略参数列表和返回值，但必须永远包含捕获列表和函数体；

