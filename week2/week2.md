
# 依赖倒置/好莱坞原则/接口隔离原则



## 作业一:请描述什么是依赖倒置原则，为什么有时候依赖倒置原则又被称为好莱坞原则？

依赖倒置原则:

- 高层模块不应该依赖底层模块,两者应该依赖抽象.

- 抽象不应该依赖具体实现,具体实现应该依赖抽象.

- 抽象是属于高层模块,不受底层模块影响,有利于高层模块复用.

在生活中,依赖倒置原则可以体现在电插口和插头上,家里的插口早已经被安装好了,各种新的电器(底层)要通电,要符合插孔的设计(抽象)的插头才能通电.

好莱坞原则:
 “不要给我们打电话，我们会给你打电话
(don't call us, we'll call you)”这是著名的好莱坞原则。 
在好莱坞，把简历递交给演艺公司(高层)后就只有回家等待。 
由演艺公司对整个娱乐项的完全控制，
演员(底层)只能被动式的接受公司的差使,在需要的环节中，
完成自己的演出.这不就是依赖倒置的体现吗!

## Cache类图作业

![](第二周作业画图.png)
