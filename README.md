# Caffe-Jacinto-Model
Caffe-Jacinto is an embedded deep learning framework. https://github.com/tidsp/caffe-jacinto 
I focused on light weight CNN and trained MobileNet SqueezeNet ShuffleNet on caffe-jacinto.
Becuase my computing hardware is pool. I only pre-trained backbones on CIFAR-100 and trained light_weight_net-SSD on VOC.
I finished 3 stage training : intial - L1 - Sparse, achieved 70% sparsity and imported caffemodel to tidl bin file.
    