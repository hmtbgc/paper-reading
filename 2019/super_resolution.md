# **Super Resolution** <br>
## **Review** <br>
- [ ] Super-Resolution via Deep Learning (**review**)<br>
(https://arxiv.org/abs/1706.09077)

## **Methods** <br>
### **SRCNN** 
- [x] Learning a Deep Convolutional Network for Image Super-Resolution <br>
(http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.642.1999&rep=rep1&type=pdf)
### **FSRCNN**
- [x] Accelerating the Super-Resolution Convolutional Neural Network  <br>
(https://arxiv.org/abs/1608.00367)
### **ESPCN**
- [x] Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network <br>(https://arxiv.org/abs/1609.05158) <br>
(*need to read again*)
### **VDSR**
- [x] Accurate Image Super-Resolution Using Very Deep Convolutional Networks<br>
(https://arxiv.org/abs/1511.04587)<br>
(*nice paper! The deeper, the better. first paper to apply residuals to SISR*)
### **DRCN**
- [x] Deeply-Recursive Convolutional Network for Image Super-Resolution)<br>
(https://arxiv.org/abs/1511.04491)<br>
(*recursive-convolution -- fewer parameters*)
### **RED**
- [x] Image Restoration Using Very Deep Convolutional Encoder-Decoder Networks with Symmetric Skip Connections<br>
(https://arxiv.org/abs/1603.09056)<br>
(*paired conv & deconv, skip-connection transfers image details & gradients*)
### **DRRN**
- [x] Image Super-Resolution via Deep Recursive Residual Network<br>
(http://openaccess.thecvf.com/content_cvpr_2017/papers/Tai_Image_Super-Resolution_via_CVPR_2017_paper.pdf)<br>
(*combination of VDSR & DRCN, global residual & local residual, very complicated structure*)
### **LapSRN**
- [x] Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution<br>
(https://arxiv.org/abs/1704.03915)<br>
(*two branches: feature extraction & image reconstruction, progressively reconstruction(upsample), new loss function(l1)*)
### **SRDenseNet**
- [x] Image Super-Resolution Using Dense Skip Connections<br>
(http://openaccess.thecvf.com/content_ICCV_2017/papers/Tong_Image_Super-Resolution_Using_ICCV_2017_paper.pdf)<br>
(*haven't read DenseNet, but skip connections do matter. low-level information should also be used for reconstruction. feature combination rather than element-wise summation*)
### **SRGAN(SRResNet)**
- [x] Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network<br>
(https://arxiv.org/pdf/1609.04802.pdf)<br>
(*GAN, perceptual loss = content loss + weight * adversial loss, content loss can be MSE(too smooth) or VGG loss(high level feature map*))
### **EDSR**
- [x] Enhanced Deep Residual Networks for Single Image Super-Resolution<br>
(https://arxiv.org/abs/1707.02921.pdf)<br>
(*remove BN layers from SRResNet, use specific pre-trained models for different up-scale*)

