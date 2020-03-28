# Keras-YOLOV3
目标检测
## 1、如何复现本文
(a) 下载权重文件，即预训练权值文件，读者也可以从0训练，将下载的模型放在model_data文件夹下。下载地址：
链接：https://pan.baidu.com/s/1w8dOvQxs_e8EfCgdGnDzXw 
提取码：v7v7 
(b) 文件说明：
logs文件夹为存放训练后的模型，model_data文件夹存放voc_classes文件，及anchors文件及预训练文件，VOCdevkit存放Annotation文件夹对应图片的xml文件，ImageSets对应Main文件夹存放数据集的信息，Images存放图像文件。
(c) 使用步骤：
voc_annotations文件用来转换yolo需要的格式；
用jupyter 打开train文件，进行训练；
打开predict文件，进行预测。
具体的实现细节可以参考。
