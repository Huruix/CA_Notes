# 引言
---
## PPT翻页过程
1. **硬件过程**
2. **软件过程**
3. **PPT翻页卡顿原因**
   1. 系统中有其他任务运行
   2. 图形多，GPU太忙
   3. 内容多，内存带宽不足
   4. 在独立显存的情况下，数据从内存到显存需要专门的机制，如直接内存访问(DMA)

## 冯诺依曼结构的优缺点
1. **本质特征：** 存储程序和指令驱动执行
2. **优点：** 自动、快速执行
3. **缺点：** 指令驱动顺序执行，CPU和存储器分开且越来越远

## 计算机的性能
1. 定义：完成一个任务所需的时间
2. $CPUtime = \frac{Seconds}{Program} = \frac{Instrutions}{Program} = \frac{Instructions}{Program} \times \frac{Cycles}{Instructions} \times \frac{Seconds}{Cycles}$
3. 