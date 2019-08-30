## Convolution-Neural-Network--Image-classification
### Construction of a Convolution Neural Network (CNN) for image classification.  The network is going to classify objects from the images from 10 different classes. The dataset used is a subset of CIFAR-100.


This repository includes 2 CNNs for classifying coarse (furniture and insects) and fine classes.

- Techniques used in order to improve network's accuracy:
 	Data augmentation and preprocessing
	Adam (Adaptive moment estimation)
	Reduce learning rate on plateau
	Early stopping
	Checkpoint saving

### Two models for our problem:
- The first model constructed was 2 different CNNs, one for coarse and one for fine categories as shown below.
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im1.png)


![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im6.png)


- The second model is a Hierarchical Deep Convolutional Neural Network (based on [1]). The image below show the architecture of the approach.
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im2.png)

#### Layers for coarse and fine classification
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im3.png)

#### Shared Layers
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im4.png)

#### Classification Results
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im5.png)

Full report is available only in greek.


References

[1] Zhicheng,Y.,Zhang,Η.,Piramuthu,R., Jagadeesh,V.,DeCoste,D., Wei,D., Yizhou,Y.,"HD­CNN: Hierarchical
Deep Convolutional Neural Network for Large ScaleVisual Recognition",IEEE International Conference on
Computer Vision (ICCV 2015)

[2] Lecun,Y.,Bottou,L.,Bengio,Y.,Haffner,P.,"Gradient­based learning applied to document
recognition",Proceedings of the IEEE ( Volume: 86 , Issue: 11), (Nov 1998 )

[3] Wang,L.,Sohmshetty,A.,Learning Image Representations to Understand and Predict
SemanticHierarchies,Stanford University

[4] Deshpande,A.,"A Beginner's Guide To Understanding Convolutional Neural Networks",CS Undergrad at UCLA
('19),Blog About GitHub Projects Resume, (2016)

[5]https://github.com/justinessert/hierarchical­deep­cnn/blob/master/hdcnn.ipynb?fbclid=IwAR1xgj5DaajG2p3aG3
uhnhkCR6WRH02cPnuny7Xqivgefu43a9n8hT_jTlU
