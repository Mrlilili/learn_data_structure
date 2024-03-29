# 数据结构的概念预算法

程序设计 = 数据结构 + 算法 

> 数据结构指的是数据直接的结构关系如何不表示，
如何存储，如何处理的问题，即按某种关系组织起来的一组数据，
再按一定的方式把它们存储在计算机的存储器中，并在这些数据上定义的一个运算集合，
这就叫做一个数据结构。

## 数据逻辑结构

- 集合：松散关系
- 线性结构：一对一关系
- 树形机构：一对多关系
- 图状结构或网状结构：多对多关系

## 数据的存储结构

- 顺序存储结构：逻辑相邻的元素存储在屋里位置也相邻的位置。
- 链式存储结构：不要求逻辑上相邻的元素在物理位置也相邻，借助指针域存储与该节点逻辑上相邻元素在内存中的地址来实现节点间的逻辑关系。
- 索引存储结构：存储元素信息的同时建立附加的索引表。
- 散列存储结构：根据元素的关键字直接计算出该元素的存储地址。

## 算法的描述

- 有限性：必须在有限的步骤之后结束。
- 确定性：每一步都有确切的含义，无二义性。
- 输入：接收零个或多个输入。
- 输出：至少一个或多个输出。
- 可行性：每一步都可以通过已经实现的基本运算的有限次运行来实现。

> 好的算法要素：正确性、可读性、健壮性、高效率、低存储量。

## 算法时间复杂度
## 算法空间复杂度