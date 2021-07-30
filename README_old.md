## Jerry He(何泽邦)'s homepage

I receive my Bsc scholar from CSU(Central South University) and Msc scholar from City University of Hong Kong.

In the former stage, my research interests including salient object detection, image layer separation, and recently my interests change to Object Detection and Segmentation.

### Publication Currently

Lin, Jiaying, Zebang He and Rynson W. H. Lau. “Rich Context Aggregation with Reflection Prior for Glass Surface Detection.” . CVPR2021

### Detection in animation scenes(*Xenoblade2* by Nintendo in current)

Dataset Samples:

<img alt="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/2021-03-22_21-47-43.mp4_9.jpg" src="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/2021-03-22_21-47-43.mp4_9.jpg" width="256" height=""><img alt="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/9.jpg" src="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/9.jpg" width="256" height="">

<img alt="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/2021-03-22_21-47-43.mp4_16.jpg" src="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/2021-03-22_21-47-43.mp4_16.jpg" width="256" height=""><img alt="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/16.jpg" src="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20image/16.jpg" width="256" height="">

The object sample(Nopon) is shown:

<img alt="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/nopon/nopong%20sample.jpg" src="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/nopon/nopong%20sample.jpg" width="256" height="">

Currently, I have tested the below networks: Yolov3, Yolov4 and RetinaNet.

Yolov3:**You Only Look Once: Unified, Real-Time Object Detection, YOLOv3: An Incremental Improvement**

Public code:
[https://github.com/ultralytics/yolov3](https://github.com/ultralytics/yolov3)

Yolov4:**YOLOv4: Optimal Speed and Accuracy of Object Detection**

public code:
[https://github.com/Tianxiaomo/pytorch-YOLOv4](https://github.com/Tianxiaomo/pytorch-YOLOv4)

RetinaNet:**Focal Loss for Dense Object Detection**

public code:
[https://github.com/NVIDIA/retinanet-examples](https://github.com/NVIDIA/retinanet-examples)


The sample result of the Yolov3(Current Best) are shown in below:


<img alt="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20video/result.gif" src="https://github.com/He-jerry/He-jerry.github.io/raw/main/Xenoblade2/teaser%20video/result.gif" width="384" height="">


However, the problem is that, although the shape/texture of the object is similar, the difference of the backgrounud will cause the different detection result.

For example, I test another sample video in different scene(Snow scene):






### Re-imlementation of some papers

**Re-implementation of image restoration:**

**CRRN: Multi-Scale Guided Concurrent Reflection Removal Network, Renjie Wan, Boxin Shi, Ling-Yu Duan, Ah-Hwee Tan, Alex C. Kot**

[https://arxiv.org/abs/1805.11802](https://arxiv.org/abs/1805.11802)

[https://github.com/He-jerry/CRRN](https://github.com/He-jerry/CRRN)

**Learning to Jointly Generate and Separate Reflections, Daiqian Ma, Renjie Wan, Boxin Shi, Alex C. Kot, Ling-Yu Duan**

[https://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Learning_to_Jointly_Generate_and_Separate_Reflections_ICCV_2019_paper.pdf](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Learning_to_Jointly_Generate_and_Separate_Reflections_ICCV_2019_paper.pdf)

[https://github.com/He-jerry/Joint](https://github.com/He-jerry/Joint)

**Deep Adversarial Decomposition: A Unified Framework for Separating Superimposed Images, Zhengxia Zou, Sen Lei, Tianyang Shi, Zhenwei Shi, Jieping Ye**

[https://openaccess.thecvf.com/content_CVPR_2020/html/Zou_Deep_Adversarial_Decomposition_A_Unified_Framework_for_Separating_Superimposed_Images_CVPR_2020_paper.html](https://openaccess.thecvf.com/content_CVPR_2020/html/Zou_Deep_Adversarial_Decomposition_A_Unified_Framework_for_Separating_Superimposed_Images_CVPR_2020_paper.html)

Official Implementation(Updated Nov 2020, thanks the official code for authors to help me correct some mistakes in the implementation of the code): [https://github.com/jiupinjia/Deep-adversarial-decomposition](https://github.com/jiupinjia/Deep-adversarial-decomposition)

My unofficial implementation: [https://github.com/He-jerry/PatchGAN](https://github.com/He-jerry/PatchGAN)   (Please refer the official implementation first, because my implementation also has some mistakes in training.)

**Stacked Conditional Generative Adversarial Networks for Jointly Learning Shadow Detection and Shadow Removal, Jifeng Wang, Xiang Li,Jian Yang**

[https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Stacked_Conditional_Generative_CVPR_2018_paper.pdf](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Stacked_Conditional_Generative_CVPR_2018_paper.pdf)

Official Implementation (no code)：[https://github.com/DeepInsight-PCALab/ST-CGAN](https://github.com/DeepInsight-PCALab/ST-CGAN)

My implementation: [https://github.com/He-jerry/ST-CGAN](https://github.com/He-jerry/ST-CGAN)

**Residual Squeeze-and-Excitation Network for Fast Image Deraining, Jun Fu, Jianfeng Xu, Kazuyuki Tasaka, Zhibo Chen**

[https://arxiv.org/abs/2006.00757](https://arxiv.org/abs/2006.00757)

[https://github.com/He-jerry/Residual-SE-Network](https://github.com/He-jerry/Residual-SE-Network)





**Re-implementation of Saliency Detection:**

**ResNeSt: Split-Attention Networks, Hang Zhang, Chongruo Wu, Zhongyue Zhang, Yi Zhu, Zhi Zhang, Haibin Lin, Yue Sun, Tong He, Jonas Mueller, R. Manmatha, Mu Li, Alexander Smola**

**Deeply Supervised Salient Object Detection with Short Connections, Qibin Hou, Ming-Ming Cheng, Xiao-Wei Hu, Ali Borji, Zhuowen Tu, Philip Torr**

[**ResNeSt**](https://arxiv.org/abs/1611.04849)

[**DSSNet**](https://openaccess.thecvf.com/content_cvpr_2017/papers/Hou_Deeply_Supervised_Salient_CVPR_2017_paper.pdf)

[https://github.com/He-jerry/DSSNet](https://github.com/He-jerry/DSSNet)



**Platform Transfer Implementation:**

**CENet: Context encoder network for 2D medical image segmentation,Zaiwang Gu, Jun Cheng, Huazhu Fu, Kang Zhou, Huaying Hao, Yitian Zhao, Tianyang Zhang, Shenghua Gao, Jiang Liu**

[https://arxiv.org/abs/1903.02740](https://arxiv.org/abs/1903.02740)

Reference implementation(Pytorch): [https://github.com/Guzaiwang/CE-Net](https://github.com/Guzaiwang/CE-Net)

My implementation(Tensorflow):[https://github.com/He-jerry/CENet-Tensorflow](https://github.com/He-jerry/CENet-Tensorflow)

**U2-Net: Going Deeper with Nested U-Structure for Salient Object Detection,Xuebin Qin, Zichen Zhang, Chenyang Huang, Masood Dehghan, Osmar R. Zaiane and Martin Jagersand**

[https://arxiv.org/pdf/2005.09007.pdf](https://arxiv.org/pdf/2005.09007.pdf)

official implementation(Pytorch):[https://github.com/xuebinqin/U-2-Net](https://github.com/xuebinqin/U-2-Net)

My unofficial implementation(Tensorflow):[https://github.com/He-jerry/U2Net-Tensorflow](https://github.com/He-jerry/U2Net-Tensorflow)

**F3Net: Fusion, Feedback and Focus for Salient Object Detection,Jun Wei, Shuhui Wang, Qingming Huang**

[https://arxiv.org/abs/1911.11445](https://arxiv.org/abs/1911.11445)

official implementation(Pytorch):[https://github.com/weijun88/F3Net](https://github.com/weijun88/F3Net)

My unofficial implementation(Tensorflow):[https://github.com/He-jerry/F3Net-Tensorflow](https://github.com/He-jerry/F3Net-Tensorflow)



### Homework of Msc Project

**3D-Project**

**ConvPoint: Generalizing discrete convolutions for unstructured point clouds**

**JSIS3D: Joint Semantic-Instance Segmentation of 3D Point Clouds with
Multi-Task Pointwise Networks and Multi-Value Conditional Random Fields**

[https://github.com/He-jerry/3D-project](https://github.com/He-jerry/3D-project)


### Support or Contact
My Email: kingofkr121908@gmail.com
