# 图解设计模式

> “Next to My Life, Software Is My Passion”——Robert C.Martin.

## 设计模式概述

工程师按照面向对象思想设计一套大型软件系统时，在考虑系统的架构时，在考虑对象的封装、继承、多态时，总不免莫名的恐惧。在无数次的失败和尝试之后，工程师往往能找到若干设计原则或设计模式的东西，似乎摸到了面向对象分析和设计（OOA/D）的精要。经典的GoF 的《设计模式：可复用面向对象软件的基础》和MVC架构等设计模式方面在这方面做了深刻的总结。深入体会之后，我们会发现设计模式背后都遵循着最基本的设计原则：单一职责原则、开放封闭原则、依赖倒置原则、接口隔离原则和Liskov替换原则。

设计模式并不是空的理论，并不是脱离实际的教条。我们处理数据类的项目时，能深刻感觉到算法和数据结构的无穷魅力；我们处理逻辑类的项目时，能深刻感觉到面向接口编程和将抽象和实现分离的思想光辉。设计模式正是以最佳实践的形式告诉我们如何处理面向对象的实际问题，诸如：类与相互通信的对象之间的组织关系，包括它们的角色、职责、协作方式几个方面？道可道，非常道。道不远人，设计模式亦然如此。

## 内容规划

> 高能彩蛋：除了经典的模式还深入分析了Android中间件使用的设计模式，原创满满！

| Process | Chapter Name | Author Name | Quality Rank\(0-10\) |  
| :---: | :--- | :---: | :---: |  
| 2% | 面向对象思想 | [面向对象的基本原则](ex_object_oriented_think.md)  | ☆ |  
| 2% | 创建型模式 | [Factory模式](pattern_create/pattern_factory_method.md) | ☆ |  
| 2% | 创建型模式 | [AbstactFactory模式](pattern_create/pattern_abs_factory.md) | ☆ |  
| 2% | 创建型模式 | [Singleton模式](pattern_create/pattern_singleton.md) | ☆ |  
| 2% | 创建型模式 | [Builder模式](pattern_create/pattern_builder.md) | ☆ |  
| 2% | 创建型模式 | [Prototype模式](pattern_create/pattern_prototype.md) | ☆ |
| 1% | 结构型模式 | Bridge模式 | ☆ |  
| 1% | 结构型模式 | Adapter模式 | ☆ |  
| 1% | 结构型模式 | Decorator模式 | ☆ |  
| 1% | 结构型模式 | Composite 模式 | ☆ |  
| 1% | 结构型模式 | Flyweight模式 | ☆ |  
| 1% | 结构型模式 | Facade模式  | ☆ |  
| 1% | 结构型模式 | Proxy模式 | ☆ |  
| 1% | 行为模式 | Template模式 | ☆ |  
| 1% | 行为模式 | Strategy模式  | ☆ |  
| 1% | 行为模式 | State模式 | ☆ |  
| 1% | 行为模式 | Observer模式 | ☆ |  
| 1% | 行为模式 | Memento模式 | ☆ |  
| 1% | 行为模式 | Mediator模式  | ☆ |  
| 1% | 行为模式 | Command模式 | ☆ |  
| 1% | 行为模式 | Visitor模式 | ☆ |  
| 1% | 行为模式 | Chain of Responsibility模式 | ☆ |  
| 1% | 行为模式 | Iterator模式 | ☆ |  
| 1% | 行为模式 | Interpreter模式 | ☆ |  
| 1% | 分层模式 | [分层架构模式](book-cn/ex_hierarchical_architecture.md) | ☆ |  
| 100% | 三层模式 | [三层架构模式](book-cn/ex_three_layer_architecture.md) | ☆ |  
| 1% | 混合模式 | 混合架构模式 | ☆ |  
