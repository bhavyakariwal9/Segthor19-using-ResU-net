# Segthor19-using-ResU-net
The recent advances in the field of computer vision has led to the wide use of Convolutional Neural Networks (CNNs) in organ segmentation of computed tomography (CT) images. Image guided radiation therapy requires the accurate segmentation of organs at risk (OARs). In this paper, we propose a 2D U-Net network to automatically segment thoracic organs at risk in computed tomography (CT) images. The architecture consists of a down sampling path to capture features and a symmetric up sampling path to obtain precise localization. SegTHOR19 is a competition timed to the conference IEEE ISBI 2019 that addresses the problem of organs at risk segmentation in Computed Tomography (CT) images. In the SegTHOR19 challenge, 40 CT scans with 4 thoracic organs (i.e., esophagus, heart, trachea and aorta) were used for training [1]. We experimented with both 2D U-net and 2D U-Net with Resnet18 architecture to train the networks. Our best results were obtained by using 2D Convolutional U-Net with ResNet18.

author: Mohit Asudani (IIIT MANIPUR)

Institution: Bennett University

email: m.asudani@iiitmanipur.ac.in

Tookit need Python 3, pytorch >= 1.0.1, fastai version 1.x.

The data path organized like: 
./dataset/train/Patient_01/GT.nii 
./dataset/train/Patient_01/Patient_01.nii

GPU used : NVIDIA® DGX-1™ (8 gpu)
           COLAB GPU
     
DATA VISUALIZATION:

<img src="https://avatars1.githubusercontent.com/u/4284691?v=3&s=200" title="Train" alt="Dataset for training"></a>
<img src="https://avatars1.githubusercontent.com/u/4284691?v=3&s=200" title="Test" alt="Data obtained by testing"></a>

Please don't hesitate to contact me if you have any question about the data, method, or code !
