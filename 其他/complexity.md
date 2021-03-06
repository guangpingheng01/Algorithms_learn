# 关于复杂度的笔记

## 时间复杂度
有几点需要**注意**的:

1. 所谓算法分析并非精确同济算法实际执行所需时间，而是针对算法中语句的执行次数做出估计，从中得到算法执行时间的信息。
2. O，表示数量级，又有点“同阶无穷大”的意思，

>即如O(f(n)),表示当n趋于无穷大时，f(n)，O(f(n))之比是一个常数。

3.常见的衰减复杂度按数量级递增排列依次为:

>常数阶O(1)、对数阶O(logn)、线性阶O(n)、线性对数O(nlogn)、平方阶O(n^2)、立方阶O(n^3)、...、k次方阶O(n^k)、指数阶O(2^n)。

4.应该尽可能使用多项式阶的算法，而避免使用指数阶的算法。


## 空间复杂度

1.对于输入数据所占的内存以及程序本身执行所需的内存，这些与算法无关或者与较算法影响较小，所以只需分析算法在实现时所需要的辅助空间。
2.若算法执行时所需要的辅助空间相对于输入数据量而言是个常数，则称这个算法为原地工作，辅助空间为O(1).



## 参考的是严蔚敏的数据结构的书上内容

![时间复杂度1](time1.jpg)
![时间复杂度2](time2.jpg)
![时间复杂度3](time3.jpg)
![空间复杂度](space.jpg)