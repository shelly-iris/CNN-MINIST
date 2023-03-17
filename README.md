# CNN-MINIST
利用TensorFlow构建CNN网络进行手写数字识别

手写数字识别是常见的图像识别任务，计算机通过手写体图片来识别图片中的字。与印刷字体不同的是，不同人的手写体风格迥异，大小不一，造成了计算机对手写识别任务的困难，通过应用深度学习和TensorFlow工具对MNIST手写数据集进行训练并建模，CNN网络对于图像的识别和分类效果很好，所以决定采用卷积神经网络实现。

网络结构图如下：

![image](https://user-images.githubusercontent.com/75011654/225789823-70a1e72d-2096-4884-8599-44232f37aca3.png)

以上网络中，用keras.layers添加了两个卷积池化层，之后又添加了dropout层，防止过拟合，最后添加了两层全连接层

可视化结果如下：

![image](https://user-images.githubusercontent.com/75011654/225789765-2997a026-5686-4ea6-bba1-3d0ddceeb95e.png)

准确率：

![image](https://user-images.githubusercontent.com/75011654/225789962-12e8118e-88ca-49bc-8667-f1695a866ab0.png)
