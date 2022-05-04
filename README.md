#### Lab computer:
---

显卡驱动+cuda+cudnn安装： https://zhuanlan.zhihu.com/p/77874628

tensorflow-gpu安装：https://zhuanlan.zhihu.com/p/157473379

注意cuda，cudnn以及python版本相匹配：https://tensorflow.google.cn/install/source_windows

environment: 
gan 用于pytorch写的GAN文件



---
Borah

Login with:

ssh -XC xxxxx@borah-login.boisestate.edu

---



## GAN


## DCGAN

train on you own dataset: https://www.topbots.com/step-by-step-implementation-of-gans-part-2/

---

- [ ] Crop all the raw images into 256 * 256
- [ ] classify the cropped images into Alligator, Block, Longitudinal, Transverse, Patching, Sealing, and Manhole
- [ ] Use GAN to train each of kind to produce fake images
- [ ] combine fake images and real images to train YOLO v5 model
