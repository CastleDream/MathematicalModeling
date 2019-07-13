**书：**

本系列数学建模教程主要参考： **西南交通大学出版社**出版的**数学建模及其应用**，由**储昌木和沈长春**主编
___

**实现工具：**

主要使用的工具是Python，而不是常规数学建模的matlab或者lingo，所以参考那本书，同时自己网上搜索代码实现。

---
**文档书写工具：** 
+ jupyter notebook
+ 产生表格 https://www.tablesgenerator.com/markdown_tables
+ 在线matlab https://octave-online.net/
---
**相关函数文档**

目测python中与数学建模相关的库最有用的就是[scipy](https://docs.scipy.org/doc/scipy/reference/)，链接到scipy文档了
+ [优化问题](https://docs.scipy.org/doc/scipy/reference/optimize.html#module-scipy.optimize)
    + python求解线性规划的函数：[scipy.optimize.linprog](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.linprog.html#scipy.optimize.linprog)
    + python求解整数规划的函数：[pulp教程](http://benalexkeen.com/linear-programming-with-python-and-pulp/)
    
---
**文档组织结构**

1.数学规划模型——根据目标函数和约束条件的形式，可将数学规划模型分为
- [x]  线性规划模型，
- [x]  整数规划模型，
- [x]  非线性规划模型，
- [x]  目标规划模型
- [x]  动态规划模型
