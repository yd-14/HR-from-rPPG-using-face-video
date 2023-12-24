# rPPG using facial videos

The measurement of heart rate holds significant importance in numerous scenarios. Primary objective of rPPG is to remotely measure heart activity without any physical contact.

In this project, we replicated the work of Yu, Zitong and Li, Xiaobai and Zhao, Guoying on **PhysNet**, A 3DCNN based DL model highly effective in accurately detecting PPG signal from videos.

>Yu, Z., Li, X., & Zhao, G. (2019). Remote Photoplethysmograph Signal Measurement from Facial Videos Using Spatio-Temporal Networks. British Machine Vision Conference.
 
![DeepLearning_rPPG](https://github.com/yd-14/HR-from-rPPG-using-face-video/assets/77013976/eeb1ed69-e665-469e-aef5-298efe9dffa2)


Trained the model on UBFC rPPG dataset for 15 epochs on using Nvidia P100 hardware provided by kaggle.

Dataset available at request: https://sites.google.com/view/ybenezeth/ubfcrppg

>S. Bobbia, R. Macwan, Y. Benezeth, A. Mansouri, J. Dubois, "Unsupervised skin tissue segmentation for remote photoplethysmography", Pattern Recognition Letters, 2017.
 
Sample output:
 
![result](https://github.com/yd-14/HR-from-rPPG-using-face-video/assets/77013976/7734421e-da32-4878-b438-e2c79461c59f)
