## 简单工厂模式
golang没有构造函数一说，所以一般会定义NewXXX函数来初始化相关类，也就是说Golang的一般推荐做法就是简单工厂。

在这个simplefactory包中只有API接口和NewAPI函数为包外可见，封装了实现细节。