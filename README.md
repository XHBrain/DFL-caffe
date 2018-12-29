# DFL-caffe
This is a caffe re-implementation of CVPR 2018 [Learning a Discriminative Filter Bank Within a CNN for Fine-Grained Recognition](https://arxiv.org/pdf/1611.09932.pdf).

趁还没有人用caffe实现，我先占个坑。根据论文设计的网络，训练非常吃显存，当然我的类别数很大（类别数我改了，防止被社会工程学）。

我提供的版本是以resnet18为基础搭建DFL，精度比原网络略高。
