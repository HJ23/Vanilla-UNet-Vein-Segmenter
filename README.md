### Vanilla U-Net based approach for retinal image segmentation

> It is well known that U-Net is network which mainly used in Segmentation tasks. In this application i implemented network from scratch using U-Net paper
[U-Net paper](https://arxiv.org/abs/1505.04597)

> RITE dataset relatively small that is why data augmentation applied (5 degree rotation for every single image)

> Here is simplified network architecture

![unet_brain_mri](https://user-images.githubusercontent.com/39130214/73118665-8f393700-3f70-11ea-9fc4-68620710d0f2.png)

!

> This repository doesnt includes any training dataset if you want to get some training material check out [RITE Dataset](https://medicine.uiowa.edu/eye/rite-dataset)


* Requirements :
  * OpenCV 
  * PyTorch
  * NumPy
  * TorchVision
  
  
> Here is a result from testset:



