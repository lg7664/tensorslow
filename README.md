# tensorslow
基于tensorflow做的一个图像识别分类项目，是我当初的毕业设计。

我主要使用的是基于机器学习的卷积神经网络，Tensorflow学习库，来实现图像的特征提取，记录和学习，从而实现图像的分类。由于个人能力有限，所以我开发的不是完整的开发一个可移植的拥有庞大数据库的图像分类系统，而是使用神经网络算法实现了图像的分类和检测。

总的来说，我的研究内容主要有：
⑴使用OS下载并解压CIFAR数据集，得到32*32像素的训练图像，测试图像和实际预测图像，并对他们进行处理，使其可以被当前的系统环境使用。
⑵介绍卷积神经网络及其激活函数和训练方法等，最后使用Tensorflow进行图像的识别分类。
⑶对CIFAR数据集进行算法训练，得到所需要的特征参数。
⑷根据特征参数对测试图像进行预 测，获得预测的准确率。
⑸根据特征参数对实际图像进行预测，并将预测的结果和实际结果进行展示。
本次使用的Tensorflow支持多种客户端语言下的安装和运行。截至版本1.12.0，绑定完成并支持版本兼容运行的语言为C和python。本次研究就是使用TensorFlow构建深度神经网络分类器对图像数据进行学习，存储数据，进而根据储存的数据对新的图像进行识别并进行分类。而且，因为在大型项目的训练过程比较长，需要的时间比较多，因此设计了断点续训的功能，当训练一定的轮次之后，系统将会将训练得到的所有参数存储在指定目录中，当因为断电或者其他原因中断训练的时候，我们可以从指定目录中获取之前训练得到的参数来继续训练，而不需要从头开始训练，保证了之前训练的价值。

以下是我运行该项目的环境：
主机参数	操作系统：Windows 10 教育版
CPU：Intel(R) Core(TM) i7-6700HQ @ 2.60GHz
系统内存：16.00 GB
GPU：NVIDIA GeForce GTX 960M
GPU内存：2 GB

开发环境	Tensorflow版本：1.2.1
IDE版本：Anaconda 4.2
开发语言：Python 3.5.2
