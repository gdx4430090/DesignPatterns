﻿简单工厂模式:负责生产对象的一个类

优点：

1、简单工厂模式解决了客户端直接依赖于具体对象的问题，客户端可以消除直接创建对象的责任，而仅仅是消费产品。简单工厂模式实现了对责任的分割。
2、简单工厂模式也起到了代码复用的作用

简单工厂模式的缺点:
1、工厂类集中了所有产品创建逻辑，一旦不能正常工作，整个系统都会受到影响
2、系统扩展困难，一旦添加新产品就不得不修改工厂逻辑，这样就会造成工厂逻辑过于复杂。

适用性:
当工厂类负责创建的对象比较少时可以考虑使用简单工厂模式
客户如果只知道传入工厂类的参数，对于如何创建对象的逻辑不关心时可以考虑使用简单工厂模式