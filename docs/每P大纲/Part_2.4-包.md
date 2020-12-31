##### 简介要放的链接:

- [Java 教程 | 菜鸟教程 (runoob.com)](https://www.runoob.com/java/java-tutorial.html)

##### 什么是Java:

- Java 是一个面向对象编程语言

- 至于面向对象是什么以后要用到的时候会说的

- 我们通常说的安装Java指的是

  安装用于运行Java字节码文件的Java虚拟机

  - ###### Java 字节码文件:

  - Java 字节码文件是编译器将我们写的代码

  - 转换成Java虚拟机可以运行的代码后的文件

  - ###### Java虚拟机:

  - Java 虚拟机可以理解为运行在系统里的系统

  - 就像是Win10和Win7这样的电脑系统一样
  
  - 只是Win10和Win7是运行在不同的电脑上
  
  - 而Java虚拟机是运行在不同的系统里
  
  - 它们的作用都是将 应用程序(.exe)或字节码文件(.class)
  
  - 运行在不同的平台上

- 也就是JRE  Java运行环境(Java Runtime Environment)
- 我们安装的JDK与JRE的区别就是一个带开发工具
- 比如编译器等 一个不带

##### Java 基本语法:

- 我在这里只讲一些可能会用到的 

- 其他的可以去 [Java 教程 | 菜鸟教程 (runoob.com)](https://www.runoob.com/java/java-tutorial.html) 看

- 首先 Java语言是大小写敏感的 也就是说  

- 对于Java编译器来说  Java 和 java 是两个不同的东西

- Java 中每条语句以英文分号结尾

- Java 中变量名, 类名, 方法名都被称为标识符

- Java 标识符必须以 A-Z a-z $ 或 _ 作为首字符

- 除了首字符之外可以用 A-Z a-z $ _ 0-9

- Java 标识符不能 以Java关键字命名 比如 class public等

- 一般尽量纯英文就行 有错的IDE一般都有提示

- Java 中 常用变量类型有 int char double

- int 为在范围:-2147483648～2147483647 的整数

- char 为单个字符

- double 为小数(一般够用)

- Java 中 单行注释用 //

- 多行注释用 /**/

- 例:

- ```java
  // 注释
  /*注释*/
  int a = /*行内注释 一般别这样用*/ 1;
  ```

- Java 中的变量声明以及赋值方法:

-  ```java
  //Java 中 这样声明一个变量
  <变量类型> <变量名>;
  //例:
  int a;
  //Java 中 这样给变量赋值
  a = 1;
  ```
  
- Java 中这是一个最简单的类:

- ```java
  class MyClass{//MyClass为类名 class为声明类用的关键字 {}中的内容为这个类的内容
      
  }
  ```

- Java 中这是一个最简单的有参数方法(Java 中的方法(Method)即为其他一些语言的函数(Function)):

- ```java
  class MyClass{//MyClass为类名 class为声明类用的关键字 {}中的内容为这个类的内容
      void MyMethod(int input){
          /*
          MyMethod为方法名 void的意思是这个方法不返回任何东西
          括号中为这个方法的参数:  括号内不写任何东西就是不需要参数
          */
      }
  }
  ```
- 其他的后面会慢慢讲到

##### Java 语言结构:

- 我在这里只讲一些可能会用到的 

- 其他的可以去 [Java 教程 | 菜鸟教程 (runoob.com)](https://www.runoob.com/java/java-tutorial.html) 看

- 最简单的一个Java程序:

- ```java
  public class HelloWorld { // public 为访问控制修饰符  意为所有地方都能调用
      public static void main(String[] args){ 
          /* 
          static为静态的 即不用创建实例即可调用, 且在所有实例里共享
      	*/
          System.out.println("Hello World");// 在控制台打印Hello World
      }
  }
  ```

- Java 的所有代码都是放在类里的

- 类里可以嵌套类

- 例:

- ```java
  public class HelloWorld {
      public static void main(String[] args){
          System.out.println("Hello World");
      }
      public class MyClass {
          public static void MyMethod(){
              //做点什么
          }
      }
  }
  ```

- 