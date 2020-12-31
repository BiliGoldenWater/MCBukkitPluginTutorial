- 代码块

  - 被{}括起来的所有代码算作一个代码块

  - 例:

  - ```java
    void Method(){
        //代码块内容
    }
    ```

- 什么是变量

  - 变量就是用来装信息的盒子
  - 不同的盒子装不同的东西

- 变量的声明

  - 变量类型 变量名;

    - 例:
    
    - ```java
        int a;
        ```

- 变量的操作

  - 变量的初始化, 赋值
    
    - 初始化: 变量的第一次赋值
      
    - 例:
    
    - ```java
      int a=5;
      int b;
      b=6;
      // 这些都算初始化
      ```
      
    - 赋值 使用=来赋值
    
    - 例:
    
    - ```java
      int a;
      a = 1;
      a = a+1;
      ```
    
  - 自增 自减 ++a a++的区别

    - 自增 将变量加上1

    - 自减 将变量减去1

    - ++a与a++的区别

    - 例:

    - ```java
      int a;
      a = 1;
      System.out.print(a++);
      System.out.println(" " + a);
      a = 1;
      System.out.print(++a);
      System.out.println(" " + a);
      ```

  - +=, -=

    - 将变量加上或减去一个值;

    - 例:

    - ```java
      int a;
      a = 1;
      a += 5;
      System.out.println(a); // 6
      a -= 4;
      System.out.println(a); // 2
      ```

- 局部变量与全局变量

  - 局部变量->当前代码块执行完毕后就销毁
  - 类变量->只要实例存在即可引用
  - 静态类变量->被所有实例共享 类没卸载就存在.
  - final变量->初始化后不可修改

- 常用变量类型

  - int->整数 [byte short long]

    - ```java
      int a = 5;
      System.out.println(a);
      ```

  - double->浮点数(小数) [float]

    - ```java
      double a = 5.5;
      System.out.println(a);
      ```

  - String->字符串

    - ```java
      String a = "abc";
      System.out.println(a);
      ```

  - char->单个字符

    - ```java
      char a = 'a';
      System.out.println(a);
      ```

- 数组

  - 使用 变量类型[] 变量名 来定义一个数组
  
  - 使用 数组变量名 = new 类型[大小] 来初始化一个数组
  
  - 例:
  
  - ```java
    int[] a;
    a = new int[5];
    //或
    int[] b = new int[5];;
    ```
  
  - 





Hello 大家好

我是Golden_Water

这期视频要讲Java的变量