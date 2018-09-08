## CNN_on_Mnist   


### 1 不同的封装实现卷积神经网络   
分别使用不同的封装，实现并训练一个卷积神经网络，在训练集和测试集上正常运行  
1）使用原生的TensorFlow API（convolutional_nn_native）  
2）使用TensorFlow--Layers（convolutional_nn_layers）   
3）使用TensorFlow--Slim（convolutional_nn_slim）   
4）使用TensorFlow--Keras（convolutional_nn_keras）  


### 2 卷积神经网络参数探索      

使用tensorflow，构造并训练一个卷积神经网络，尝试不同的参数设置，在测试集上达到超过99%的准确率。

可调整参数：   
1）卷积kernel size  
2）卷积kernel 数量    
3）学习率    
4）正则化因子    
5）权重初始化分布参数等