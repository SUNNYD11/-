- 定义函数两种方法，函数声明（会变量提升），函数表达式（无变量提升）

- 递归：一个函数通过名字调用自身的情况下构成的

  ```
  var factorial = (function f(num){
   if (num <= 1){
   return 1;
   } else {
   return num * f(num-1);
   }
  }); 
  ```

- 闭包，指有权访问另一个函数作用域中的变量的函数。常见方式就是在一个函数内部创建另一个函数（由于闭包会携带包含它的函数的作用域，因此会比其他函数占用更多的内存，过度使用闭包会导致内存占用过多。）

- this对象，基于函数的执行环境绑定，在全局函数中，this 等于 window，而当函数被作为某个对象的方法调用时，this 等
  于那个对象。

- 
