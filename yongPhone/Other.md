# Tips

## 动态代理

## 领域对象

![](pictures/tips1.png)

## 声明式事务

以方法为单位，进行事务控制；抛出异常，事务回滚。

最小的执行单位为方法。决定执行成败是通过是否抛出异常来判断的，抛出异常即执行失败