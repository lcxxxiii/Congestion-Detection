# MobileNetV2 with Spatial Attention module for traffic congestion recognition in surveillance image
    Traffic congestion recognition is essential for road traffic condition monitoring and improving transportation operation efficiency. 
    Recent works have proposed using computer vision to develop cost-effective traffic congestion detection systems. 
    This paper proposed a custom framework for recognizing traffic congestion using a trained advanced CNNs model on highway surveillance images. 
    The proposed CNNs model uses an attention mechanism that significantly helps the network performing better. 
    Specifically, a spatial attention module is proposed to aggregate model features and increase representational power.
    The framework also uses the Grad-CAM approach for visual interpretability and localization of traffic congestion in surveillance images. 
    Judging from the results of Grad-CAM, attention-integrated models can localize traffic congestion in surveillance images better. 
    Exploring the optimal model choice for edge device deployment: MobileNetV2 is considered the best model choice for this task due to its lowest FLOPs and params. 
    Furthermore, the accuracy of MobileNetV2 with attention module on the test set exceeds that of several advanced CNNs models such as VGG16, GoogLeNet, ResNet50, Efficientnetb0, DenseNet121.
    For a selected dataset of real-world traffic congestion images, test accuracy of 98.58\% strongly supports the model's efficiency in recognizing traffic congestion rendering image samples. 
    Not only that, the high recall rate of 98.62\% indicates that the false negative values of the model are negligible.
    In addition, proposed model also achieves 98.82\% on the UCSD dataset, which as same as sort-of-the-art method.
    Our model is developed under the Pytorch framework using python3.8.

## Traffic congestion detection dataset

The dataset can be available at https://1drv.ms/u/s!ApttMupT-3rjg0OyEGDwORZ73EDd?e=bjPJwC.


