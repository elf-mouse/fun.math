## 常用的函数阶

下面是在分析算法的时候常见的函数分类列表。所有这些函数都处于 `n` 趋近于无穷大的情况下，增长得慢的函数列在上面。 `c` 是一个任意常数。

| 符号                | 名称                                 |
| ------------------- | ------------------------------------ |
| O(1)                | 常数（阶，下同）                     |
| O(log\*n)           | 迭代对数                             |
| O(log n)            | 对数                                 |
| O[(log n)^c]        | 多对数                               |
| O(n)                | 线性，次线性                         |
| O(n log n)          | 线性对数，或对数线性、拟线性、超线性 |
| O(n^2)              | 平方                                 |
| O(n^c),Integer(c>1) | 多项式，有时叫作“代数”（阶）         |
| O(c^n)              | 指数，有时叫作“几何”（阶）           |
| O(n!)               | 阶乘，有时叫做“组合”（阶）           |

```
n = 16;

O(1)     =      1 step
O(log n) =      4 steps // assumed base 2
O(n)     =     16 steps
O(n^2)   =    256 steps
O(2^n)   = 65,536 steps
```