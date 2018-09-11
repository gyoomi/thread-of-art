###Java并发机制的底层实现原理
- volatile的应用
>volatile是轻量级的synchronized，它在多处理器开发中保证了共享变量的“可见性”
如果volatile变量修饰符使用恰当
的话，它比synchronized的使用和执行成本更低，因为它不会引起线程上下文的切换和调度

- 1.volatile的定义与实现原理
>Java语言规范第3版中对volatile的定义如下：Java编程语言允许线程访问共享变量，为了
 确保共享变量能被准确和一致地更新，线程应该确保通过排他锁单独获得这个变量。Java语言
 提供了volatile，在某些情况下比锁要更加方便。如果一个字段被声明成volatile，Java线程内存
 模型确保所有线程看到这个变量的值是一致的。
 
 - 2.synchronized的实现原理与应用
 >

 
 