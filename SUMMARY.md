# 目录

* [《深入浅出JVM字节码》](README.md)
* [序言](xuyan.md)
* [第一章 Java虚拟机基础](chapter01/README.md)
  * [为什么会出现StackOverflowError](chapter01/01.md)
  * [JVM运行时内存结构](chapter01/02.md)
  * [线程、栈与栈桢](chapter01/03.md)
  * [局部变量表与操作数栈](chapter01/04.md)
  * [基于栈的指令集架构](chapter01/05.md)
  * [本章小结](chapter01/06.md)
* [第二章 深入理解Class文件结构](chapter02/README.md)
  * [class文件结构](chapter02/00.md)
  * [动手实现class文件结构解析器](chapter02/01.md)
  * [解析魔数](chapter02/02.md)
  * [解析版本号](chapter02/03.md)
  * [解析常量池](chapter02/04.md)
  * [解析class文件的访问标志](chapter02/05.md)
  * [解析this与super符号引用](chapter02/06.md)
  * [解析接口表](chapter02/07.md)
  * [解析字段表](chapter02/08.md)
  * [解析方法表](chapter02/09.md)
  * [解析class文件的属性表](chapter02/10.md)
  * [解析整个Class文件结构](chapter02/11.md)
  * [属性二次解析](chapter02/12.md)
  * [本章小结](chapter02/13.md)
* [第三章 字节码指令集](chapter03/README.md)
  * [从Hello Word出发](chapter03/01.md)
  * [字段与方法描述符](chapter03/02.md)
  * [读写局部变量表与操作数栈](chapter03/03.md)
  * [基于对象的操作](chapter03/04.md)
  * [访问静态字段与静态方法](chapter03/05.md)
  * [调用方法的四条指令](chapter03/06.md)
  * [不同类型返回值对应的指令](chapter03/07.md)
  * [创建数组与访问数组元素](chapter03/08.md)
  * [条件分支语句的实现](chapter03/09.md)
  * [循环语句的实现](chapter03/10.md)
  * [异常处理的实现](chapter03/11.md)
  * [本章小结](chapter03/12.md)
* [第四章 深入理解类加载](chapter04/README.md)
  * [动态加载类的两种方式](chapter04/01.md)
  * [类加载过程](chapter04/02.md)
  * [双亲委派模型](chapter04/03.md)
  * [自定义类加载器](chapter04/04.md)
  * [本章小结](chapter04/05.md)
* [第五章 ASM快速上手]()
  * [框架简介]()
  * [访问者模式在ASM框架中的应用]()
  * [在项目中使用ASM]()
  * [创建类并创建方法]()
  * [给类添加字段]()
  * [改写类并改写方法]()
  * [创建类并实现接口]()
  * [继承类并重写父类方法]()
  * [本章小结]()
* [第六章 实战一：JDK与Cglib动态代理]()
  * [JDK动态代理实现原理分析]()
  * [动手实现JDK动态代理]()
  * [Cglib动态代理实现原理分析]()
  * [动手实现Cglib动态代理]()
  * [本章小结]()
* [第七章 实战二：APM数据采集之探针埋点]()
  * [Instrumentation简介]()
  * [编写Java Agent插件]()
  * [在类加载之前修改类的字节码]()
  * [使用ASM为方法插入埋点]()
  * [在类加载之后修改类的字节码]()
  * [本章小结]()
* [第八章 进阶篇]()
  * [深入理解类型检查与栈映射桢]()
  * [深入理解泛型与泛型方法调用]()
* [字节码实战开源项目](opensourceprojects/README.md)
  * [实现类Spring框架@Async注解功能的asyncframework](opensourceprojects/asyncframework.md)
  * [一款轻量级的分布式调用链路追踪Java探针vine](opensourceprojects/vine.md)
  * [运行时解析json生成class的json-class-generator](opensourceprojects/jcg.md)
  * [JavaAgent入门级项目Beemite](opensourceprojects/beemite.md)

