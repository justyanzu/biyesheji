实验记录全过程：https://www.kaggle.com/code/justyanzu805412/mobilenetv2


基于传统方法和深度学习的人脸活体检测的研究及应用（毕业设计）
技术栈：Python(TensorFlow, OpenCV)、MobileNetV2、CABM 注意力机制、多特征融合
设计简介：在三个公开数据集下进行实验。
针对传统方法优化：融合HSV/YCbCr颜色空间 LBP 特征，SVM分类HTER达2.61%，较单特征提升16%；
深度学习突破：设计多分支 MobileNetV2 架构，引入CABM注意力机制，对提取特征进行特征融合，引入CABM注意 力机制进一步优化模型；
在公开数据集CASIA-FASD下进行消融实验，探讨不同颜色空间 下的特征融合，通道注意力与空间注意力模块的先后顺序对模型的影响，实现检测精度提升。
