## 一、什么是双端队列 

栈（stack），顶部和底部，添加新项和删除新项都在顶部“后进先出”  LIFO

队列（Queue），队首和队尾， 添加新项的一端称为队尾，移除项的一端称为队首  “先进先出”  FIFO  队尾[6,5,4,3,2]队首

双端队列(Deque), 首部和尾部， 可以在前面或者后面添加新项，同样， 可以从任意端移除现有项。从某种意义上，双端队列这种混合线性结构提供了单个数据结构中的栈和队列的所有能力  尾部[ ]首部

从某种意义上， 双端队列这种混合线性结构提供了单个数据结构中的栈和队列的所有能力

## 二、Deque的抽象数据类型和python实现

·  Duque() 创建一个空的deque。不需要参数  返回空的deque

·  addFront（item）  将新项添加到deque的首部  需要item作为参数不返回任何内容

· addRear(item)    将新项添加到deque的尾部   需要item作为参数  不返回任何内容

·  removeFront()   从deque中删除首项， 不需要参数   deque被修改

`  removeRear()   从deque中删除尾项 不需要参数  deque 被修改

`isEmpty()  测试deque是否为空  不需要参数返回布尔值

` size()  返回deque中的项数  不需要参数返回一个整数



## 三、练习题一

判断输入的字符是不是：回文字符

山西运煤车煤运西山

上海自来水来自上海