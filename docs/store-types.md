# 存储

## 存储类别关键字

`auto` `register` `static` `extern` `_Thread_local` `typedef`

## 存储类型

存储类别|存储期|作用域|链接|声明方式
------|------|-----|----|------
自动|自动|块|无|块内
寄存器|自动|块|无|块内，使用关键字`register`
静态外部链接|静态|文件|外部|所有函数外
静态内部链接|静态|文件|内部|所有函数外，使用关键字`static`
静态无链接|静态|块|无|块内，使用关键字`static`

## 类型限定符

- `const` 恒常性
- `volatile` 易变性
- `restrict` 提高编译优化，只能用于指针(C99)
- `_Automic` (C11)