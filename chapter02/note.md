
2.感知机
   perceptron:
   二类分类的现行分类模型
   输入为实例的特征向量 输出为实例的类别
   去+1和-1的值
   
   求出将训练数据进行现行划分的分离超平面
   基于误分类的损失函数 利用梯度下降法对损失函数进行及消化 求得感知机模型
   简单易于实现的优点
   分为 原始形式和对偶形式 是神经网络和支持向量机的基础
   
   2.1
   感知机模型
   定义:假设输入空间 特征空间 future space是X属于R的n次之内
   输出空间是 Y 等于集合+1 -1 x属于X 代表书里的特征向量 对英语输出空间的点y属于Y 表示势力的类别
   有输入空间到输出空间的如下函数
   
   函数x等于 sign(w乘以x加b)
   sign函数的特征
   