# Weakly-Supervised-Segmentation-of-SAR-Imagery-Using-Superpixel-and-Hierarchically-Adversarial-CRF
this code implements the method proposed in paper "Weakly Supervised Segmentation of SAR Imagery Using Superpixel and Hierarchically Adversarial CRF". if it helps you, please kindly cite this paper. https://www.mdpi.com/2072-4292/11/5/512

  *Read_img_Gan.py : transfer the large-scale SAR image into superpixels, which will be used to Fine-tune the Hierarchy CGAN
  
  *Hierarchy_Semi_DCGAN_FangChengGang.py : define the  Hierarchy CGAN
  
  *DCGAN_FangChengGang_16.py ： define the TCGAN
  
  *DCGAN_FangChengGang_64.py : define the BCGAN
  
  *torchtools.py : define some tool functions
  
  *utils_GAN.py : define some tool functions
  
  *main.py : the main function of this project
  
any problem please email me : mafeimf@buaa.edu.cn
