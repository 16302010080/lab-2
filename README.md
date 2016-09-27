#Lab2
>课程目标：

>>1.首先了解作用域的概念，然后学习字符串的操作以及条件判断的使用，最后利用所学完成一个小程序。

>>2.学习java code style，书写具有良好风格的代码。

#作用域

>通常来说，一段程序代码中所用到的名字并不总是有效/可用的，而限定这个名字的可用性的代码范围就是这个名字的作用域。

>案例分析：

>```
if(true){
  int a = 1;
}
System.out.println(a);
```

>这是一段错误的代码，如果不清楚原理的同学，可以放在main函数中运行。

>原因就是 a 定义在 if 中，作用域也仅仅于此，出了这里便无效了。

>而要达到：在条件语句中得到某个值，然后再外面打印。可以这样实现：

>```
int a;
if(true){
  a = 1;
}
System.out.println(a);
```
>在这里， `int a`

