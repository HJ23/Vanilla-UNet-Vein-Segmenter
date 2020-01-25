### Vanilla U-Net based approach for retinal image segmentation

> It is well known that U-Net is network which mainly used in Segmentation tasks. In this application i implemented network from scratch using U-Net paper
[U-Net paper](https://arxiv.org/abs/1505.04597)

> RITE dataset relatively small that is why data augmentation applied (5 degree rotation for every single image)(256x256x3)

> Here is simplified network architecture

![unet_brain_mri](https://user-images.githubusercontent.com/39130214/73118665-8f393700-3f70-11ea-9fc4-68620710d0f2.png)

!

> This repository doesnt includes any training dataset if you want to get some training material check out [RITE Dataset](https://medicine.uiowa.edu/eye/rite-dataset)


* Requirements :
  * OpenCV 
  * PyTorch
  * NumPy
  * TorchVision

!

> Learning Curve :
![download (2)](https://user-images.githubusercontent.com/39130214/73126642-d6eeab80-3fce-11ea-8999-9add48e5d7a6.png)
  
> Here is a result from testset:
![download (1)](https://user-images.githubusercontent.com/39130214/73125569-ad7b5300-3fc1-11ea-932a-ad263872346c.png)




