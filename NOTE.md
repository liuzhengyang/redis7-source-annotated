# 一些通用注释

## 线程安全问题

redis中的数据结构，都是由单线程进行访问的，所以也不用考虑线程安全问题。

## do{} while(0)

代码中有不少do{} while(0)这样的宏定义，目的是保证代码能够让宏展开不会出错
参考[Why use apparently meaningless do-while and if-else statements in macros](https://stackoverflow.com/questions/154136/why-use-apparently-meaningless-do-while-and-if-else-statements-in-macros)