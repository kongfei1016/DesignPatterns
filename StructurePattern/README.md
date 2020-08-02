# 结构型设计模式总结

## Intro

结构型设计模式主要总结了一些类或对象组合在一起的经典结构，这些经典的结构可以解决一些特定应用场景的问题。

结构型模式包括：代理模式、桥接模式、装饰器模式、适配器模式、外观（门面）模式、组合模式、享元模式。

## 总结

### 适配器模式（Adapter）

适配一下不兼容的接口，work together

### 桥接模式（Bridge）

将抽象部分与它的实现部分分离，使得它们都可以独立地变化。

### 组合模式（Composite）

将对象组合成树形结构以表示 “部分-整体” 的层次结构，组合模式使得用户对单个对象和组合对象的使用具有一致性

### 装饰模式（Decorator）

动态地给一个对象添加一些额外的职责和功能

### 外观/门面模式（Facade）

定义一组高层接口让子系统更易用

### 享元模式（Flyweight）

复用对象，减少内存占用

### 代理模式（Proxy）

由代理对象控制对原对象的引用

## More

可以描述成树形结构的父子关系用组合

分离抽象和实现独立变化用桥接

增加额外功能职责用装饰

控制访问用代理

复用对象用享元

封装底层子系统接口用外观、门面

兼容老系统接口用适配器

## Reference

- <https://github.com/WeihanLi/DesignPatterns>
- [适配器模式](./AdapterPattern.html)
- [桥接模式](./BridgePattern.html)
- [组合模式](./CompositePattern.html)
- [装饰模式](./DecoratorPattern.html)
- [外观/门面模式](./FacadePattern.html)
- [享元模式](./FlyweightPattern.html)
- [代理模式](./ProxyPattern.html)